https://code.visualstudio.com/docs/copilot/customization/prompt-files

Prompt files are Markdown files that define reusable prompts for common development tasks like generating code, performing code reviews, or scaffolding project components. They are standalone prompts that you can run directly in chat, enabling the creation of a library of standardized development workflows.

They can include task-specific guidelines or reference custom instructions to ensure consistent execution. Unlike custom instructions that apply to all requests, prompt files are triggered on-demand for specific tasks.

Note

Prompt files are currently experimental and may change in future releases.

Prompt files are Markdown files and use the `.prompt.md` extension and have this structure:

- **Header** (optional): YAML frontmatter
    
    - `description`: Short description of the prompt
    - `mode`: Chat mode used for running the prompt: `ask`, `edit`, or `agent` (default).
    - `model`: Language model used when running the prompt. If not specified, the currently selected model in model picker is used.
    - `tools`: Array of tool (set) names that can be used. Select **Configure Tools** to select the tools from the list of available tools in your workspace. If a given tool (set) is not available when running the prompt, it is ignored.
- **Body**: Prompt instructions in Markdown format
    
    Reference other workspace files, prompt files, or instruction files by using Markdown links. Use relative paths to reference these files, and ensure that the paths are correct based on the location of the prompt file.
    
    Within a prompt file, you can reference variables by using the `${variableName}` syntax. You can reference the following variables:
    
    - Workspace variables - `${workspaceFolder}`, `${workspaceFolderBasename}`
    - Selection variables - `${selection}`, `${selectedText}`
    - File context variables - `${file}`, `${fileBasename}`, `${fileDirname}`, `${fileBasenameNoExtension}`
    - Input variables - `${input:variableName}`, `${input:variableName:placeholder}` (pass values to the prompt from the chat input field)
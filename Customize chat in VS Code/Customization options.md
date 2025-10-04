There are five main ways to customize chat in Visual Studio Code. These options work independently or you can combine them for more comprehensive customization.

### 1. Custom Instructions

[Custom instructions](https://code.visualstudio.com/docs/copilot/customization/custom-instructions) let you define common guidelines or rules in a Markdown file for tasks like generating code, performing code reviews, or generating commit messages. With custom instruction, you describe _how_ a specific task should be performed. VS Code can automatically apply these instructions or you can choose to include them in specific chat requests.

Use custom instructions to:

- Specify coding practices, preferred technologies, or project requirements, so generated code follows your standards
- Provide guidelines about how a commit message or pull request title and description should be structured
- Set rules for code reviews, such as checking for security vulnerabilities, performance issues, or adherence to coding standards

### 2. Prompt files

[Prompt files](https://code.visualstudio.com/docs/copilot/customization/prompt-files) let you define reusable prompts for common and repeatable development tasks in a Markdown file. Prompt files are standalone prompts that you can run directly in chat. You can include task-specific context and guidelines about how the task should be performed. Combine prompt files with custom instructions to ensure consistent execution of complex tasks.

Use prompt files to:

- Create reusable prompts for common coding tasks, such as scaffolding a new component, API route, or generating tests
- Define prompts for performing code reviews, such as checking for code quality, security vulnerabilities, or performance issues
- Create step-by-step guides for complex processes or project-specific patterns
- Define prompts for generating implementation plans, architectural designs, or migration strategies

### 3. Chat modes

[Chat modes](https://code.visualstudio.com/docs/copilot/customization/custom-chat-modes) are a way to create a specialist assistant for specific roles or tasks, like a database administrator, front-end development, or planning. Within a chat mode Markdown file, you describe its scope and capabilities, which tools it can access, and a preferred language model.

Use chat modes to:

- Create a chat mode for planning, where the AI has read-only access to the codebase and can only generate implementation plans
- Define a research chat mode, where the AI can reach out to external resources to explore new technologies or gather information
- Create a front-end developer chat mode, where the AI can only generate and modify code related to front-end development

### 4. Language models

[Language models](https://code.visualstudio.com/docs/copilot/customization/language-models) let you choose from different AI models optimized for specific tasks. You can switch between models to get the best performance for code generation, reasoning, or specialized tasks like vision processing. Bring your own API key to access more models or have more control over model hosting.

Use different language models to:

- Use a fast model for quick code suggestions and simple refactoring tasks
- Switch to a more capable model for complex architectural decisions or detailed code reviews
- Bring your own API key to access experimental models or use locally hosted models

### 5. MCP and Tools


[MCP and tools](https://code.visualstudio.com/docs/copilot/customization/mcp-servers) let you connect external services and specialized tools through Model Context Protocol (MCP). This extends chat capabilities beyond code to interact with databases, APIs, and other development tools.

Use MCP and tools to:

- Connect database tools to query and analyze data without leaving your development environment
- Integrate with external APIs to fetch real-time information or perform actions


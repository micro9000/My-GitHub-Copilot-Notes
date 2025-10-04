Copilot Edits is available in Visual Studio Code, Visual Studio, and JetBrains IDEs. Use Copilot Edits to make changes across multiple files directly from a single Copilot Chat prompt. Copilot Edits has the following modes:

#### [Edit mode](https://docs.github.com/en/copilot/get-started/features#edit-mode)

Edit mode is only available in Visual Studio Code and JetBrains IDEs.

Use edit mode when you want more granular control over the edits that Copilot proposes. In edit mode, you choose which files Copilot can make changes to, provide context to Copilot with each iteration, and decide whether or not to accept the suggested edits after each turn.

Edit mode is best suited to use cases where:

- You want to make a quick, specific update to a defined set of files.
- You want full control over the number of LLM requests Copilot uses.

#### [Agent mode](https://docs.github.com/en/copilot/get-started/features#agent-mode)

Use agent mode when you have a specific task in mind and want to enable Copilot to autonomously edit your code. In agent mode, Copilot determines which files to make changes to, offers code changes and terminal commands to complete the task, and iterates to remediate issues until the original task is complete.

Agent mode is best suited to use cases where:

- Your task is complex, and involves multiple steps, iterations, and error handling.
- You want Copilot to determine the necessary steps to take to complete the task.
- The task requires Copilot to integrate with external applications, such as an MCP server.
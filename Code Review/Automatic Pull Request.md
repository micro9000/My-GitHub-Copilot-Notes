By default, Copilot will only review a pull request if it's assigned to the pull request in the same way you would assign a human reviewer. However:

- Individual users on the Copilot Pro or Copilot Pro+ plan can configure Copilot to automatically review all pull requests they create.
- Repository owners can configure Copilot to automatically review all pull requests in the repository that are created by people with access to Copilot.
- Organization owners can configure Copilot to automatically review all pull requests in some or all of the repositories in the organization where the pull request is created by a Copilot user.

The triggers for automatic code review depend on the configuration settings:

- **Basic setting**:
    - When a pull request is created as an "Open" pull request.
    - The first time a "Draft" pull request is switched to "Open".
- **Review new pushes**:
    - Every time a new commit is pushed to the pull request.
- **Review draft pull requests**:
    - Pull requests are automatically reviewed while they are still drafts—before being switched to "Open".
# acdh frontend devcontainer

[devcontainer](https://containers.dev/) for frontend development.

includes:

- node.js v24
- git
- github cli
- os-dependencies for playwright

## how to use

create a `.devcontainer/devcontainer.json` file in the repository root:

```json
{
  "image": "ghcr.io/acdh-oeaw/devcontainer-frontend:24",
  "customizations": {
    "vscode": {
      "extensions": [
        // vs code extensions, which should be pre-installed.
      ]
    }
  }
}
```

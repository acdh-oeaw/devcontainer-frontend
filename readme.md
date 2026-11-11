# acdh frontend devcontainer

[devcontainer](https://containers.dev/) for frontend development.

includes:

- node.js v26 (Debian Trixie)
- pnpm v12 (uses project-specific versions from `packageManager`)
- git
- github cli
- os-dependencies for playwright
- docker-in-docker

## how to use

create a `.devcontainer/devcontainer.json` file in the repository root:

```jsonc
{
  "image": "ghcr.io/acdh-oeaw/devcontainer-frontend:26",
  "postCreateCommand": "pnpm install && pnpm exec playwright install",
  "forwardPorts": [3000],
  "customizations": {
    "vscode": {
      "extensions": [
        // vs code extensions, which should be pre-installed.
      ]
    }
  }
}
```

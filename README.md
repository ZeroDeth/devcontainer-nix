# Devcontainer for Nix

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/ZeroDeth/devcontainer-nix)

VSCode devcontainer for Nix

This devcontainer contains Nix and hooks to install nix recipe as devcontainers.
This is the base image that can be used to extend your own devcontainer based on nix.

## Getting started

The host machine must have:

* VS Code
  * https://code.visualstudio.com/download
* WSL 2 (if running Windows)
  * https://ripon-banik.medium.com/how-to-install-wsl2-offline-b470ab6eaf0e
* DevContainers VS Code Extension
  * Download from https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers

## Tasks

### build

```
podman build --progress=plain -t devcontainer:latest .
```

### run

```
podman run --rm -it devcontainer:latest
```

# flutter devcontainer

[![Publish Docker image](https://github.com/Derrick56007/flutter_devcontainer/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/Derrick56007/flutter_devcontainer/actions/workflows/docker-publish.yml)

Requirements
------------
- Docker: https://docs.docker.com/get-docker/
- Git: https://git-scm.com/downloads
- VSCode: https://code.visualstudio.com/download
- VSCode Remote Dev Pack: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack

Install
--------------

```bash
git clone https://github.com/Derrick56007/flutter_devcontainer.git
```

Usage
------------
1. Start VS Code
2. Run the Remote-Containers: Open Folder in Container and choose flutter_devcontainer

Example
------------
```
flutter run -d web-server --web-hostname=0.0.0.0 --web-port=3000
```
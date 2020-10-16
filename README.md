# Devcontainer for Python

## Using within you project

Add `.devcontainer/devcontainer.json` to your repository.

```json
{
  "image": "ghcr.io/hspaans/python-devcontainer:latest",
  "name": "Python",
  "settings": {
    "terminal.integrated.shell.linux": "/bin/bash"
  },
  "appPort": [],
  "postCreateCommand": "",
  "remoteUser": "vscode",
  "extensions": [
    "github.vscode-pull-request-github",
    "ms-python.python",
    "redhat.vscode-yaml"
  ]
}
```

## Available version

| Python Version | Container Tag | Status    |
|:--------------:|:-------------:|:---------:|
| 3.9.0          | 3.9.0         | Published |
| 3.8.6          | 3.8.6         | Published |

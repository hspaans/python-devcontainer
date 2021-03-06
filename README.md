# Devcontainer for Python

> THIS PROJECT IS ARCHIVED
>
> See [hspaans/python-template](https://github.com/hspaans/python-template) as an alternative.

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

## Versions

The container is based on [LTS](https://en.wikipedia.org/wiki/Long-term_support) distribution versions with official support and fall within N and N-1. The *latest*-tag is an experimental tag to test future releases.

| Platform | Version | End of support |                              Image                               |
| :------: | :-----: | :------------: | :--------------------------------------------------------------: |
|  Python  |   3.7   |   2023-06-27   |    [hspaans/python-devcontainer:3.7][python-devcontainer:3.7]    |
|  Python  |   3.8   |    2024-10     |    [hspaans/python-devcontainer:3.8][python-devcontainer:3.8]    |
|  Python  |   3.9   |    2025-10     |    [hspaans/python-devcontainer:3.9][python-devcontainer:3.9]    |
|  Python  |   3.10  |                | [hspaans/python-devcontainer:latest][python-devcontainer:latest] |

[python-devcontainer:latest]: ghcr.io/hspaans/python-devcontainer:latest
[python-devcontainer:3.7]: ghcr.io/hspaans/python-devcontainer:3.7
[python-devcontainer:3.8]: ghcr.io/hspaans/python-devcontainer:3.8
[python-devcontainer:3.9]: ghcr.io/hspaans/python-devcontainer:3.9

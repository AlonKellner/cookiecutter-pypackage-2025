# {{ cookiecutter.project_name }}

[![PyPI version](https://badge.fury.io/py/{{ cookiecutter.pypi_package_name }}.svg)](https://badge.fury.io/py/{{ cookiecutter.pypi_package_name }})
[![CI Status](https://github.com/{{ cookiecutter.__gh_slug }}/actions/workflows/ci-orchestrator.yml/badge.svg)](https://github.com/{{ cookiecutter.__gh_slug }}/actions/workflows/ci-orchestrator.yml)
[![Docs Status](https://github.com/{{ cookiecutter.__gh_slug }}/actions/workflows/docs.yml/badge.svg)](https://github.com/{{ cookiecutter.__gh_slug }}/actions/workflows/docs.yml)
[![All time downloads](https://static.pepy.tech/badge/{{ cookiecutter.pypi_package_name }})](https://pepy.tech/project/{{ cookiecutter.pypi_package_name }})
[![Weekly Downloads](https://static.pepy.tech/badge/{{ cookiecutter.pypi_package_name }}/week)](https://pepy.tech/project/{{ cookiecutter.pypi_package_name }})  

[![Python versions](https://img.shields.io/pypi/pyversions/{{ cookiecutter.pypi_package_name }}.svg)](https://pypi.org/project/{{ cookiecutter.pypi_package_name }}/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Py Stack: astral.sh](https://img.shields.io/badge/py%20stack-astral.sh-30173d.svg)](https://github.com/astral-sh)
[![Open in Dev Containers](https://img.shields.io/static/v1?label=devcontainer&message=Open&color=blue)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/{{ cookiecutter.__gh_slug }})
[![Cursor](https://img.shields.io/static/v1?label=-&message=Cursor&color=black)](https://cursor.com/downloads)
[![Claude Code](https://img.shields.io/static/v1?label=-&message=Claude%20Code&color=d77253)](https://www.anthropic.com/claude-code)

{{ cookiecutter.project_short_description }}

## Features

* TODO

## 🚀 Quick Start

### Installation

```bash
# Install from PyPI
pip install {{ cookiecutter.pypi_package_name }}

# Or install from source
git clone https://github.com/{{ cookiecutter.__gh_slug }}.git
cd {{ cookiecutter.pypi_package_name }}
pip install -e .
```

### Basic Usage

* TODO

## 📖 Documentation

* [User Guide](docs/user-guide.md) - Complete usage instructions
* [Examples](docs/examples.md) - Common use cases and examples

## 🤝 Contributing

We welcome contributions! Please see our
[Contributing Guide](CONTRIBUTING.md) for details.

### Development Setup

#### Prerequisites
* [Docker](https://www.docker.com/get-started/)
* [VSCode](https://code.visualstudio.com/download)/[Cursor](https://cursor.com/downloads) (or any IDE with [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers) support)
* [Generate a GPG key and add it to github](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key)
* [Configure a GPG key as your signing key](https://docs.github.com/en/authentication/managing-commit-signature-verification/telling-git-about-your-signing-key)

#### Steps

* `git clone https://github.com/{{ cookiecutter.__gh_slug }}.git`
* Add a [github access token](https://github.com/settings/personal-access-tokens) to ./.devcontainer/.env:

  ```bash
  echo "GITHUB_PERSONAL_ACCESS_TOKEN=<token-here>" > ./.devcontainer/.env
  ```

* Open using VSCode (or Cursor):
  * `ctrl+shift+p`/`cmd+shift+p`
  * Type "Reopen"
  * Select `Reopen in Container`
  * Wait until everything finished loading/running

* Init commit:

  ```bash
  git add .
  git commit -m "init: cookiecutter"
  git push
  ```

* Start using your new repo!

#### MCP

The current MCP servers that this repo supports are:
1. [`github-mcp-server`](https://github.com/github/github-mcp-server) (Remote)
2. [`repomix`](https://github.com/yamadashy/repomix) (Local)
3. [`mcp-language-server`](https://github.com/isaacphi/mcp-language-server) (Local)

#### [Claude Code](https://www.anthropic.com/claude-code)

The `pre-commit` setup in this repo uses `claude` code to
automatically review changes.  
By default, `claude` will not be configured and will automatically
pass in the `pre-commit`.  

If you want to use `claude` to review changes, you can read about
[Claude Code Deployment](https://docs.anthropic.com/en/docs/claude-code/third-party-integrations).

## 📝 License

This project is licensed under the MIT License - see the
[LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

* Built with modern Python tooling ([astral.sh stack](https://github.com/astral-sh), [tox stack](https://github.com/tox-dev))
* Created with [Cookiecutter](https://github.com/cookiecutter/cookiecutter) and
  the [AlonKellner/cookiecutter-pypackage-2025](https://github.com/AlonKellner/cookiecutter-pypackage-2025) project
  template (fork of [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage))

## 📊 Project Status

* **Development Status**: Alpha
* **Python Support**: 3.10+
* **License**: MIT
* **Maintainer**: [{{ cookiecutter.full_name }}](mailto:{{ cookiecutter.email }})

---

## Made with ❤️ by the {{ cookiecutter.project_name }} community

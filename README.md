# Cookiecutter PyPackage 2025

[Cookiecutter](https://github.com/cookiecutter/cookiecutter) template for a Python package.

*   GitHub repo: [https://github.com/AlonKellner/cookiecutter-pypackage-2025/](https://github.com/AlonKellner/cookiecutter-pypackage-2025/)
*   Free software: MIT license
*   Discord: [https://discord.gg/PWXJr3upUE](https://discord.gg/PWXJr3upUE)

## Features

*   Testing setup with pytest
*   GitHub Actions testing: Setup to easily test for Python 3.10, 3.11, 3.12, and 3.13
*   Auto-release to [PyPI](https://pypi.python.org/pypi) when you push a new tag to master (optional)
*   Command line interface using [Typer](https://typer.tiangolo.com/)
*   [astral.sh](https://github.com/astral-sh) stack ([uv](https://docs.astral.sh/uv/), [ruff](https://docs.astral.sh/ruff/), [ty](https://docs.astral.sh/ty/))

## **2025 EXTRA FEATURES**
*   Modern tooling ([tox](https://tox.wiki/en/4.28.4/), [typos](https://github.com/crate-ci/typos), [ties](https://alonkellner.com/ties/), [commitlint](https://commitlint.js.org/), [mkdocs-material](https://squidfunk.github.io/mkdocs-material/))
*   Security ([devcontainers](https://code.visualstudio.com/docs/devcontainers/containers), [pip-audit](https://github.com/pypa/pip-audit), [trivy](https://trivy.dev/latest/))
*   Formatters & Linters for all file types ([biomejs](https://biomejs.dev/), [yamlfmt](https://github.com/google/yamlfmt) [taplo](https://taplo.tamasfe.dev/), [rumdl](https://docs.rs/rumdl/latest/rumdl/), [lychee](https://lychee.cli.rs/))
*   AI Agent Supercharged ([Cursor](https://docs.cursor.com/en/welcome), [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview), [MCP](http://modelcontextprotocol.io/docs/getting-started/intro), [lintok](https://github.com/AlonKellner/lintok))

## Quickstart

[Install uv](https://docs.astral.sh/uv/getting-started/installation/) if you haven't installed it yet.

Generate a Python package project:

```bash
uvx cookiecutter https://github.com/AlonKellner/cookiecutter-pypackage-2025.git
```

Then:

*   Create a repo and put it there.
*   [Register](https://packaging.python.org/tutorials/packaging-projects/#uploading-the-distribution-archives) your project with PyPI.
*   Release your package by pushing a new tag to master.
*   To activate the docs using github-pages:
    * Go to your repository on GitHub
    * `Settings -> Pages -> Build and deployment -> Branch`
    * Select `gh-pages`
    * Open your docs under `https://your-username.github.com/your-repo-name`

## Not Exactly What You Want?

Don't worry, you have options:

### Fork This / Create Your Own

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

### Similar Cookiecutter Templates

Explore other forks to get ideas. See the [network](https://github.com/AlonKellner/cookiecutter-pypackage-2025/network) and [family tree](https://github.com/AlonKellner/cookiecutter-pypackage-2025/network/members) for this repo.

### Or Submit a Pull Request

I also accept pull requests on this, if they're small, atomic, and if they
make my own packaging experience better.

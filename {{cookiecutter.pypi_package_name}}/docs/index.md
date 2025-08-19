# Welcome to {{ cookiecutter.project_name }}

{{ cookiecutter.project_short_description }}

## 🚀 Quick Start

### Installation

```bash
# Install using uv
uv add {{ cookiecutter.pypi_package_name }}

# or using pip
pip install {{ cookiecutter.pypi_package_name }}

# Or install from source
git clone git://github.com/{{ cookiecutter.__gh_slug }}
cd {{ cookiecutter.project_slug }}
uv pip install -e .
```

### Basic Usage

```python
import {{ cookiecutter.project_slug }}
```

## 📖 Advanced docs

- [User Guide](user-guide.md) - Complete usage instructions
- [Examples](examples.md) - Common use cases and examples

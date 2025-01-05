# KaiMCP

A simple MCP (Model Context Protocol) implementation project.

## Setup

We strongly recommend installing FastMCP with [uv](https://docs.astral.sh/uv/), as it is required for deploying servers:

```bash
# Create a new virtual environment in .venv directory
uv venv

# Activate the virtual environment
source .venv/bin/activate  # On Unix/macOS

# Install the project and its dependencies from pyproject.toml
uv pip sync pyproject.toml
```

Note: on macOS, uv may need to be installed with Homebrew (`brew install uv`) in order to make it available to the Claude Desktop app.


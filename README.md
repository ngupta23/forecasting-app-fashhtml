# forecasting-app-fashhtml
Forecasting App using FastHTML

## Setup

```bash
# Initialize a uv project
uv init

# create a venv for the project
uv venv --python 3.10

# activate the env
source .venv/bin/activate

# Install the dependencies
# using uv: This will also add it to project.toml and add it to the venv
uv add python-fasthtml
uv add pre-commit

# using pip with uv:  this will not add it to project.toml, only install in the venv
uv pip install python-fasthtml
uv pip install pre-commit
```


```bash
# Run precommit
pre-commit run
```
## How to contribute to Air Quality CLI

Thank you for considering contributing to Air Quality CLI!

### Submitting Updates

Include the following in your patch:

- Use [Black](https://github.com/psf/black) to format your code. This and other tools will run automatically if you install [pre-commit](https://github.com/pre-commit/pre-commit-hooks) using the instructions below.

- Update README.md about new changes if it affects the sub-commands.

- Use [mypy](https://github.com/python/mypy) to check static typing on the codebase.

### First time setup

- Clone the repo locally.

```bash
git clone https://github.com/yankeexe/air-quality-cli
```

- Create a virtualenv

```bash
python3 -m venv venv

# activate virtualenv
source venv/bin/activate
```

### Install Air Quality CLI in editable mode with development dependencies.

```bash
pip install -e .[dev]
```

### Install the pre-commit hooks.

```bash
pre-commit install
```

Start coding 🚀

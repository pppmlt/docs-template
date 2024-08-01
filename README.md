# Docs-Template

Cookiecutter template to create documentation with obsidian and mkdocs.

### Usage

```
cookiecutter https://github.com/pppmlt/docs-template
```

### Development setup

- prequisites:
  - `python` (>=3.8)
  - `uv` (test with 0.2.32)
- setup
``` shell
git clone https://github.com/pppmlt/docs-template
cd docs-template
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
pre-commit install
```

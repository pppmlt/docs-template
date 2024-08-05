# Docs-Template

Copier template to create documentation with obsidian and mkdocs.

### Usage

```
copier copy https://github.com/pppmlt/docs-template [DESTINATION]
```

### Development setup

- prequisites:
  - `python` (>=3.8)
  - `uv` (tested with 0.2.32)
- setup
``` shell
git clone https://github.com/pppmlt/docs-template
cd docs-template
uv venv
source .venv/bin/activate
uv pip install -r requirements.txt
pre-commit install
```

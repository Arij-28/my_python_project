# my_python_project

Minimal Python project with:
- **pytest** for unit tests
- **flake8** for linting
- **GitHub Actions** workflow to run lint + tests on every push / pull request

## Requirements
- Python 3.11+ recommended

## Setup
```bash
python -m venv .venv
# macOS/Linux
source .venv/bin/activate
# Windows (PowerShell)
# .venv\Scripts\Activate.ps1

pip install -r requirements.txt
```

## Run tests
```bash
pytest
```

## Run linter
```bash
flake8 .
```

## CI
Workflow file: `.github/workflows/python-ci.yml`

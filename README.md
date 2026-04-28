# Ruff CI Repository

This repository demonstrates pre-commit hooks and CI gates using ruff.

## Setup

Install pre-commit:
```bash
pip install pre-commit ruff==0.4.4
pre-commit install
```

## Workflow

- Pre-commit hooks catch ruff violations locally
- CI gate on PR ensures violations don't merge

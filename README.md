# code4leb_scp01

[![CI](https://github.com/ChristoYusj/code4leb_scp01/actions/workflows/ci.yml/badge.svg)](https://github.com/ChristoYusj/code4leb_scp01/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)

A lightweight Python starter repository with clean project standards for contributors and maintainers.

## Features

- Consistent code formatting and linting with Black, isort, and Flake8
- CI checks via GitHub Actions
- Contributor guidance and a repository code of conduct
- MIT licensed for open collaboration

## Quickstart

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements-dev.txt
```

## Usage example

Run local quality checks:

```bash
black --check .
isort --check-only .
flake8 .
```

Run tests (if `tests/` exists):

```bash
pytest -q
```

## Environment variables

No required environment variables are currently needed to run checks in this repository.
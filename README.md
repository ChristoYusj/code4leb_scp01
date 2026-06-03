# code4leb_scp01

[![CI](https://github.com/ChristoYusj/code4leb_scp01/actions/workflows/ci.yml/badge.svg)](https://github.com/ChristoYusj/code4leb_scp01/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A lightweight Python starter repository with contributor standards and automated quality checks.

## Features

- Clean project layout with Python package scaffolding
- GitHub Actions CI for formatting, linting, and tests
- Contributor-friendly templates and standards
- Consistent formatting configuration (Black, isort, flake8)

## Quickstart

```bash
git clone https://github.com/ChristoYusj/code4leb_scp01.git
cd code4leb_scp01
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -U pip
pip install -e .
pip install -r requirements-dev.txt
```

## Usage example

```bash
python -m code4leb_scp01
```

Expected output:

```text
code4leb_scp01 is set up and ready.
```

## Environment variables

This project does not require any environment variables by default.
If you add integrations later, document new variables here and in your deployment setup.

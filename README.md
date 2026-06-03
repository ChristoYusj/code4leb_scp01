# code4leb_scp01

[![CI](https://github.com/ChristoYusj/code4leb_scp01/actions/workflows/ci.yml/badge.svg)](https://github.com/ChristoYusj/code4leb_scp01/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

A lightweight starter repository configured to be clean, contributor-friendly, and ready for basic Python CI checks.

## Features
- Clear project overview and quick-start docs
- Basic GitHub Actions CI for lint, format checks, and tests
- Standard repository metadata files (`LICENSE`, `CONTRIBUTING`, `CODE_OF_CONDUCT`)
- Python-oriented ignore rules and formatting/linting defaults

## Quick Start
```bash
git clone https://github.com/ChristoYusj/code4leb_scp01.git
cd code4leb_scp01
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install --upgrade pip
pip install -r requirements-dev.txt
```

## Usage Example
This repository currently focuses on project setup and quality tooling.

```text
code4leb_scp01/
├── README.md
├── pyproject.toml
├── requirements-dev.txt
└── .github/workflows/ci.yml
```

## Development
- Run formatter check: `black --check .`
- Run linter: `flake8 .`
- Run tests (if present): `pytest -q`

## Contributing
Please see [CONTRIBUTING.md](./CONTRIBUTING.md).

## License
This project is licensed under the [MIT License](./LICENSE).

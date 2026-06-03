# Contributing

Thanks for your interest in contributing.

## Development setup

1. Fork and clone the repository.
2. Create and activate a virtual environment.
3. Install dependencies:

```bash
pip install -U pip
pip install -e .
pip install -r requirements-dev.txt
```

## Quality checks

Run checks before opening a pull request:

```bash
python -m black --check .
python -m isort --check-only .
python -m flake8 .
python -m pytest -q
```

If no tests are present yet, `pytest` may report that no tests were collected.

## Pull request guidelines

- Keep PRs focused and small.
- Add or update documentation when behavior changes.
- Ensure CI passes before requesting review.

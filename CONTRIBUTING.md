# Contributing

Thanks for contributing to `code4leb_scp01`.

## Local setup
1. Create and activate a virtual environment.
2. Install tooling:
   ```bash
   pip install -r requirements-dev.txt
   ```

## Quality checks
Run before opening a PR:

```bash
black --check .
flake8 .
pytest -q
```

## Pull requests
- Keep changes focused and small.
- Include a clear description of what changed and why.
- Link related issues when available.

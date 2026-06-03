# Contributing

Thanks for your interest in improving this project.

## Getting started

1. Fork the repository and create a feature branch.
2. Create and activate a virtual environment.
3. Install dependencies:
   ```bash
   pip install -r requirements-dev.txt
   ```
4. Run checks before opening a PR:
   ```bash
   black --check .
   isort --check-only .
   flake8 .
   pytest -q
   ```

## Pull request guidelines

- Keep PRs focused and small.
- Include a clear description of what changed and why.
- Ensure CI passes before requesting review.


# Contributing

Thanks for your interest in contributing!

## Quick Start
1. Fork the repo and create your branch from `main`.
2. If you add code, please keep Google Colab compatibility in mind (no breaking changes to the original notebooks).
3. Use clear, small pull requests focused on one change at a time.

## Environment
```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Data
- Do **not** commit sensitive or internal data.
- Use `data/sample_wells.csv` as a schema reference only.

## Issues
- Use the GitHub Issues tab.
- Provide steps to reproduce, expected behavior, and environment details.

## Pull Requests
- Describe what changed and why.
- Include screenshots for visual updates (plots, maps, etc.).
- CI is not configured; maintainers will run sanity checks manually.

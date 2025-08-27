# GitHub Actions Workflows

Continuous-integration bits that keep the repo healthy.

## Included
- `lint.yml` — minimal smoke test:
  - sets up Python 3.10
  - installs `requirements.txt`
  - runs a tiny check (`import pandas, numpy`)

## Why
- Proves the environment is reproducible.
- Catches obvious breaks when you push changes.

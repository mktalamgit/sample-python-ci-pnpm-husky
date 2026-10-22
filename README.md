# sample-python-ci-pnpm-husky

Sample Python project with GitHub Actions CI, pnpm, and Husky.

## Local setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements-dev.txt
pnpm install
pnpm install --lockfile-only
```

Commit `pnpm-lock.yaml` after generating it.
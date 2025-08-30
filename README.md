# Mirror repository

This repository is a GitHub mirror of an upstream repository. It is kept in sync using a GitHub Actions workflow that periodically clones the upstream repository with `--mirror` and pushes it to this repository.

Important:
- The workflow requires either:
  - secret `UPSTREAM_REPO` with the upstream HTTPS clone URL (no auth for public repos), or
  - secrets `UPSTREAM_REPO_URL` (HTTPS URL) and `UPSTREAM_TOKEN` (PAT with read access) for private upstreams.
- Default branch: `main`
- The workflow runs on schedule and can be triggered manually.

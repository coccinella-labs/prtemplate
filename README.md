# small-pr-template

A lightweight, opinionated Pull Request template for keeping PRs small,
focused, and easy to review.

## Goal
Reduce review fatigue by enforcing:
- Single-purpose PRs
- Small, atomic changes
- Clear intent and rollback paths

## What’s included
- `.github/pull_request_template.md` — ready-to-use PR template

## How to use

### Option 1: Copy into an existing repo
```bash
mkdir -p .github
curl -o .github/pull_request_template.md \
https://raw.githubusercontent.com/bniladridas/small-pr-template/main/.github/pull_request_template.md
```

# release-please-demo

Tiny Node.js repo to test **release-please** on GitHub Actions.

## How it works
- Push Conventional Commits to `main`. The action opens/updates a **Release PR**.
- Merge that Release PR → GitHub Release + tag like `v0.1.1`.

## Conventional Commit examples
- `fix: correct minor bug` → patch
- `feat: add new endpoint` → minor
- `feat!: break API` → major

# universal-codebase

## Releasing
This project uses [semantic-release](https://semantic-release.gitbook.io/) for automated versioning and releases. Use these commit types:
- `feat:` for new features (minor bump).
- `fix:` for bug fixes (patch bump).
- Add `BREAKING CHANGE:` in the footer for major bumps.

# Universal Codebase

A flexible template for any project.

## Getting Started
1. Clone: `git clone <repo-url>`
2. Install: `npm install`
3. Run tests: `npm test`

## Structure
- `src/` - Placeholder code (remove or replace dummy files).
- `tests/` - Placeholder tests (optional, remove or expand).
- `.github/workflows/` - CI/CD pipelines.

## Notes
- Dummy files (e.g., `src/dummy.js`, `tests/dummy.test.js`) are placeholders. Remove or replace them when adding real functionality.
- Semantic-release automates versioning on `main`.
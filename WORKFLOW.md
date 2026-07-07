# Workflow Rules

## Branches

- `main` represents production-ready code.
- `staging` represents code ready for testing before production.
- `develop` represents reviewed development work.
- `feature/*` branches are temporary branches created for specific tasks.

## Development Flow

1. Developers create feature branches from `develop`.
2. Developers push their work to the feature branch.
3. Developers open a Pull Request into `develop`.
4. The Technical Team Leader reviews the Pull Request.
5. Approved changes are merged into `develop`.
6. `develop` is merged into `staging` for testing.
7. `staging` is merged into `main` for production release.
8. Feature branches are deleted after merge.

## Rules

- No direct push to `main`.
- No direct push to `staging`.
- No direct push to `develop`.
- All changes must go through Pull Requests.
- Production changes must be reviewed before release.
# Contributing

Thanks for contributing to an OGonline repository. These guidelines apply to every repository in the organization unless a repository provides its own `CONTRIBUTING.md`.

## Branches

Create a branch from the repository's default (or integration) branch using one of these prefixes:

| Prefix     | Use for                                  |
| ---------- | ---------------------------------------- |
| `feature/` | New functionality                        |
| `fix/`     | Bug fixes                                |
| `hotfix/`  | Urgent fixes for production              |
| `chore/`   | Maintenance, tooling and dependencies    |
| `docs/`    | Documentation only                       |

Use short, descriptive, kebab-case names, for example `feature/contact-form` or `fix/header-overflow`.

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/). Write commit messages in English:

```
<type>(<scope>): <short description>
```

Allowed types:

- `feat`: a new feature
- `fix`: a bug fix
- `docs`: documentation changes
- `style`: formatting, no code change
- `refactor`: code change that neither fixes a bug nor adds a feature
- `test`: adding or updating tests
- `chore`: maintenance, build or tooling changes

Examples:

```
feat(forms): add newsletter signup form
fix(header): prevent menu overflow on small screens
docs(readme): describe local setup
```

## Pull requests

- Open a pull request for every change; do not push directly to protected branches.
- Fill in the pull request template: what changed, why it was needed, and screenshots or recordings for UI changes.
- Every pull request needs at least one approving review before it is merged.
- Make sure all checks (build, lint, type checks) pass.
- Merge using squash or merge commit, according to the repository's settings.
- Delete the branch after merging.

## Secrets and personal data

- Never commit secrets, API keys, passwords, tokens or `.env` files.
- Use environment variables and the team's secret manager instead.
- Do not include personal data in code, commits, issues, logs or screenshots.
- If a secret is committed by accident, rotate it immediately and report it; removing the commit alone is not enough.

## Security issues

Do not report security vulnerabilities in public issues. See [SECURITY.md](SECURITY.md).

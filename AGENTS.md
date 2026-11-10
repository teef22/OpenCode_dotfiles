# Global conventions

## Commits and PR Titles

Use conventional commit-style messages and PR titles:

- `type(scope): subject`.
- Type: valid are `feat`, `fix`, `docs`, `chore`, `refactor`, and `test`
- Scope: is optional; use the affected package or area when helpful, e.g. `core`, `opencode`, `tui`, `app`, `desktop`, `sdk`, or `plugin`
- Subject: imperative mood, lowercase, no trailing period, max 72 characters
- Body: optional for simple changes, or when the title alone makes the change 100% clear
- Breaking changes: use `!` after type/scope or a `BREAKING CHANGE:` footer
- Do not include unrelated changes in one commit
- Stage only relevant files; do not commit secrets, `.env`, or generated files unless explicitly asked

Before committing, show the proposed commit message and changed files for approval.

## Contributing to UnisonOS

Thank you for contributing. Security and accessibility are first-class requirements.

### Ground rules
- Keep secrets out of source control. Do not commit `.env` files or tokens.
- Follow the data-classification policy (public, internal, sensitive, highly-sensitive) and avoid logging sensitive data.
- Write tests for new code; include negative and abuse-case tests when touching auth, policy, or IO.
- Run linters/formatters before opening PRs. Use the provided pre-commit config where available.
- Prefer small, reviewed PRs; at least one reviewer is required for protected branches.

### Pull request checklist
- [ ] Tests and linting pass locally or in CI.
- [ ] Security impact considered (authz, input validation, least privilege).
- [ ] Dependencies are pinned; no unreviewed downloads at runtime.
- [ ] Documentation updated (README, docs, or code comments).

### Reporting security issues
Use the process in `SECURITY.md`. Do not open public issues for vulnerabilities.

### Developer environment
- Use the devcontainer/WSL/Docker devstack where provided to reduce drift.
- Use sample `.env.example` files only as templates; source secrets from Vault/Secret Manager or your chosen secure store.

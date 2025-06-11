## Git Branching

- Use the following branch prefixes:
  - `feature/` – for new features (e.g., `feature/add-dark-mode`)
  - `bugfix/` – for fixing issues (e.g., `bugfix/delete-button-bug`)
  - `hotfix/` – for urgent production issues

- Always branch off from `main` and submit a Pull Request (PR).

## Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) format:

- `feat:` – new feature
- `fix:` – bug fix
- `docs:` – documentation only
- `refactor:` – code change that doesn’t add new feature or fix a bug
- `chore:` – maintenance tasks (e.g., dependencies)

**Examples:**
- `feat: add error priority tagging`
- `fix: resolve localStorage sync bug`

## Pull Request Guidelines

- Link to related issue using `Closes #issue_number`
- Explain what you changed and why
- Request review from a team member
- All PRs must be approved before merging

## SLA (Service-Level Agreement)

We aim to maintain fast response times:

-  Bug issues: triaged within **24 hours**, fixed within **72 hours**
-  Feature requests: reviewed within **3 days** of PR submission
- 🛠 Tech debt: reviewed within **5 days**

Use issue labels like `sla/24h`, `sla/72h`, etc., to track timelines.

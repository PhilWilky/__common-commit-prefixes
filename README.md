# Common Commit Prefixes

This repository serves as a quick reference for using **Conventional Commits** to keep commit messages structured and meaningful.

## Conventional Commit Prefixes

| Prefix     | Meaning |
|------------|---------|
| `feat:`    | A new feature |
| `fix:`     | A bug fix |
| `refactor:` | Code refactoring (no new features or bug fixes) |
| `perf:`    | Performance improvements |
| `docs:`    | Documentation updates (e.g., README, comments) |
| `style:`   | Code style changes (e.g., formatting, missing semicolons) |
| `test:`    | Adding or updating tests |
| `chore:`   | Maintenance tasks (e.g., dependency updates, build scripts) |
| `ci:`      | Changes to CI/CD configuration |
| `revert:`  | Reverting a previous commit |

## Example Commit Messages:

- `feat: Implement dynamic pricing for shop items`
- `fix: Resolve issue with customer queue not updating`
- `perf: Optimize database queries for faster loading`
- `docs: Add API documentation for authentication endpoints`
- `chore: Bump dependency versions`

## Why Use Conventional Commits?

- 🏷️ **Clear History** - Makes commit history easy to read.
- 🔄 **Automated Changelog** - Helps generate changelogs automatically.
- 📦 **Consistent Standard** - Useful for teams and open-source contributions.

---

### 4. Commit and Push Changes
```sh
git add README.md
git commit -m "docs: Add commit prefix reference"
git push origin main

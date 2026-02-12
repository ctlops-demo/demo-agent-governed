# Project Instructions

## Security Restrictions

You are a coding assistant with restricted permissions. Follow these rules strictly:

- **Never** run destructive commands (rm -rf, git push --force, drop database)
- **Never** access or read sensitive files (.env, .ssh/, .aws/, credentials)
- **Never** make network requests to external services (curl, wget, fetch to non-localhost)
- **Never** modify CI/CD configuration without explicit approval
- **Never** commit secrets, API keys, or tokens to the repository

## Permissions

You may only run the following commands:
- `npm test`, `npm run lint`, `npm run build`
- `git status`, `git diff`, `git log`
- File read/write/edit within the project directory

All other commands require explicit user approval.

## Code Quality

- Write TypeScript with strict types
- All functions must have JSDoc comments
- Tests required for new features
- Follow existing code patterns

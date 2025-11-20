# Sandisk 2025 March Repository

This repository demonstrates proper Git workflow and commit message formatting standards.

## Commit Message Standards

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification for all commit messages. This ensures:

- **Consistency**: All commits follow the same format
- **Clarity**: Each commit clearly states what was changed and why
- **Traceability**: Easy to track features, fixes, and changes
- **Automation**: Commit messages can be parsed by tools for release notes

## Documentation

- **[COMMIT_GUIDELINES.md](./COMMIT_GUIDELINES.md)**: Detailed guidelines for writing proper commit messages
- **[examples/](./examples/)**: Example files with well-formatted commits

## Problem Statement Reference

This work addresses the issue referenced as "commit 3e12df97335" by establishing clear commit message formatting standards. Rather than having ambiguous commit messages like "commit 3e12df97335", "fixed stuff", or "WIP", this repository now has:

1. Documented guidelines for commit messages
2. Examples of properly formatted commits
3. A clear structure for future contributions

## Contributing

When contributing to this repository, please follow the commit message guidelines in COMMIT_GUIDELINES.md. Each commit should:

1. Use a clear type prefix (feat, fix, docs, etc.)
2. Include a concise subject line (≤50 characters)
3. Provide a detailed body explaining the change (if needed)
4. Reference related issues in the footer (if applicable)

## Examples

### Good Commit Message
```
feat(auth): add two-factor authentication

Implement 2FA using TOTP for enhanced security. Users can enable
2FA in their account settings and will be prompted for a code
after entering their password.

Closes #123
```

### Poor Commit Message
```
fixed stuff
```

See COMMIT_GUIDELINES.md for more examples and detailed explanations.

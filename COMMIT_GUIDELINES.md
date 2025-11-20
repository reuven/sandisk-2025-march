# Commit Message Guidelines

This document outlines the commit message format standards for this repository.

## Format

A well-formatted commit message consists of three parts:

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Type
The type should be one of the following:
- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation changes
- **style**: Code style changes (formatting, missing semicolons, etc.)
- **refactor**: Code refactoring without adding features or fixing bugs
- **test**: Adding or updating tests
- **chore**: Changes to build process or auxiliary tools

### Scope
Optional. The scope specifies the place of the commit change (e.g., component, file, feature)

### Subject
- Use imperative mood ("add" not "added" or "adds")
- Don't capitalize the first letter
- No period at the end
- Limit to 50 characters

### Body
Optional. Provides detailed explanation of the change:
- Use imperative mood
- Explain what and why, not how
- Wrap at 72 characters

### Footer
Optional. Reference issues, breaking changes, etc.

## Examples

### Good Commit Messages:
```
feat(user): add email validation

Implement email validation for user registration form to ensure
valid email addresses are collected. This includes format validation
and domain verification.

Closes #123
```

```
fix(auth): resolve token expiration issue

Update token refresh logic to handle edge case where tokens expire
during active user sessions. Now tokens are refreshed 5 minutes
before expiration.

Fixes #456
```

```
docs: update README with setup instructions

Add detailed setup instructions for new developers including
prerequisites, installation steps, and common troubleshooting tips.
```

### Poor Commit Messages:
- "fixed stuff"
- "updates"
- "commit 3e12df97335"
- "WIP"
- "temp"

## Reference
Based on [Conventional Commits](https://www.conventionalcommits.org/) specification.

# Contributing to 0x3 Team

Thank you for your interest in contributing. This document outlines our standards and process.

## Getting Started

1. **Get repository access**:
   - For a public repository, fork it to your account.
   - For a private repository, use an authorized organization branch or
     coordinate access with the maintainers.
2. **Clone** the repository or your fork locally.
3. **Create a branch** for your work: `git checkout -b feat/your-feature-name`
4. **Make your changes** following our code standards.
5. **Test** your changes locally.
6. **Commit** with a clear message.
7. **Push** and open a pull request.

## Branch Naming

| Type | Prefix | Example |
|---|---|---|
| Feature | `feat/` | `feat/add-auth-module` |
| Bug fix | `fix/` | `fix/null-pointer-crash` |
| Security | `sec/` | `sec/patch-xss-vuln` |
| Docs | `docs/` | `docs/update-readme` |
| Refactor | `refactor/` | `refactor/extract-utils` |

## Commit Messages

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): subject

body (optional)

footer (optional)
```

Examples:
```
feat(auth): add OAuth2 token refresh logic
fix(api): handle null response from upstream
sec(deps): update openssl to 3.4.2
docs(readme): add installation instructions
```

## Code Standards

- Follow existing code style in each repository
- Keep functions small and focused
- Add tests for new functionality
- Document public APIs
- No secrets, tokens, or credentials in code

## Pull Request Process

1. **Fill out the PR template** completely
2. **Link related issues** in the description
3. **Ensure CI passes** before requesting review
4. **Request review** from the appropriate team (core for features, security for security-related changes)
5. **Address review feedback** promptly
6. **Squash commits** if asked by reviewer

## Security Vulnerabilities

**Do not open a public issue for security vulnerabilities.** See [SECURITY.md](./SECURITY.md) for our disclosure policy.

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Questions?

Email [hi@0x3.dev](mailto:hi@0x3.dev) or open a discussion in the relevant repository.

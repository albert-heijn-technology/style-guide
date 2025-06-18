# Contributing to AH Technology style guide

Thank you for your interest in contributing to the AH Technology style guide. This document provides guidelines for contributing to this project.

## Getting started

### Creating issues

Before contributing, check if an issue already exists for the change you want to make. If not, please create a new issue by:

1. Go to the [Issues page](https://github.com/albert-heijn-technology/style-guide/issues)
2. Click "New Issue"
3. Choose the appropriate issue template or create a blank issue
4. Provide a clear title and description of the problem or feature request
5. Add relevant labels to help categorize the issue

## Making contributions

### Pull requests

When you're ready to contribute:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes following the project's style guide
4. Test your changes locally
5. Commit your changes using conventional commits
6. Sign off on your commits, required for Developer Certificate of Origin (DCO) check
7. Push your branch to your fork
8. Create a pull request

### Conventional commits

This project uses [Conventional Commits](https://www.conventionalcommits.org/) for commit messages. The format is:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Types:**

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation changes
- `style`: Changes that do not affect the meaning of code (white-space, formatting, etc.)
- `refactor`: Code changes that neither fix a bug nor add a feature
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to build process or auxiliary tools

**Examples:**

```
feat: add new heading punctuation rule
fix: correct date format validation
docs: update README with installation instructions
```

### Signing off commits

All commits must be signed off to pass the Developer Certificate of Origin (DCO) check. Add the `-s` flag when committing:

```bash
git commit -s -m "feat: add new style rule"
```

This adds a "Signed-off-by" line to your commit message indicating that you agree to the terms of the DCO.

### Linking pull requests to issues

When creating a pull request, link it to the related issue by adding a git trailer in the pull request description:

```
Closes: #123
```

Or use one of these other keywords:
- `Fixes: #123`
- `Resolves: #123`
- `Closes: #123`

You can also reference issues without closing them:
- `References: #123`
- `Related to: #123`

## Code review process

1. All pull requests require review before merging
2. Address any feedback from reviewers
3. Ensure all checks pass (including DCO and any automated tests)
4. A maintainer merges the pull request once approved

## Questions

If you have questions about contributing, please:

- Check existing issues and discussions
- Create a new issue with the "question" label
- Contact the maintainers through the project's communication channels

# Commit Message Template

Please use the following template for your commit messages to ensure they comply with the commitlint rules.

## Commit Message Structure

A commit message consists of a header, body, and footer. The header is mandatory and must follow the format outlined below. The body and footer are optional but recommended for providing additional context and references.

```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

## Header

### Type

The type must be one of the following:

- **feat**: A new feature
- **fix**: A bug fix
- **docs**: Documentation changes
- **refactor**: Code refactoring without adding features or fixing bugs
- **chore**: Routine tasks (e.g., updating build tasks, package manager configs)

### Scope

The scope is mandatory and should be one of the following:

- **scripts** scripts
- **lib** application code
- **build** package json
- **test** test cases
- **docs** documentation
- **ci** ci/cd github actions
- **performance** performance improvements

### Subject

The subject should be a brief summary of the change. It must follow these rules:

- Start with a capital letter
- Use sentence-case
- Do not exceed 100 characters

## Body

The body is optional but recommended for providing additional context about the commit. Use the body to explain what changes were made and why. Wrap the body text at 72 characters.

## Footer

The footer is optional and should contain any references or metadata, such as issue numbers or breaking changes.

## Examples

### Example 1

```
feat(lib): Added https server

This commit adds support for https server for node application.

BREAKING CHANGE: this change might impact running nodejs server.
```

### Example 2

```
fix(security): Fix vulnerability in authentication module

This commit addresses a vulnerability in the authentication module that could allow unauthorized access to user accounts.

Closes #123
```

### Example 3

```
chore(test-cases): Update test case documentation for new API endpoints

Added detailed descriptions and examples for the new API endpoints introduced in version 2.0.
```

Please adhere to this template to maintain a consistent commit history and improve collaboration within the project.

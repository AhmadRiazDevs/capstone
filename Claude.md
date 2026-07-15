# CLAUDE.md

# Project Guidelines

This document defines the development standards, coding conventions, and workflow for this repository. Any AI assistant or contributor should follow these guidelines when making changes.

---

# Tech Stack

This project may use the following technologies:

- JavaScript (ES6+)
- Node.js
- Git & GitHub
- npm
- VS Code
- Claude Code

Additional frameworks and libraries may be added as the project evolves.

---

# Coding Conventions

## General

- Write clean, readable, and maintainable code.
- Keep functions focused on a single responsibility.
- Avoid unnecessary complexity.
- Remove unused code and imports.

## Naming Conventions

### Variables
Use **camelCase**.

```js
const userName;
const totalPrice;
```

### Functions
Use descriptive **camelCase** names.

```js
createUser();
calculateTotal();
```

### Classes
Use **PascalCase**.

```js
UserService
ProductManager
```

### Files

- JavaScript files: camelCase
- Components/Classes: PascalCase
- Configuration files: lowercase

---

# Project Structure

The repository should follow a modular structure.

```
project-root/
│
├── src/
│   ├── components/
│   ├── services/
│   ├── utils/
│   └── assets/
│
├── docs/
├── public/
├── README.md
├── LICENSE
├── .gitignore
└── CLAUDE.md
```

Each folder should have a clear responsibility and avoid mixing unrelated functionality.

---

# Commit Message Style

This project follows the **Conventional Commits** specification.

Examples:

```
feat: add user authentication

fix: resolve login validation issue

docs: update README

style: format source code

refactor: simplify authentication logic

test: add unit tests for user service

chore: update project dependencies
```

Keep commits small and focused on a single change.

---

# Development Workflow

1. Pull the latest changes from the main branch.
2. Create a new feature branch.
3. Implement the required changes.
4. Test the application.
5. Review the code for quality.
6. Commit using Conventional Commits.
7. Push the branch to GitHub.
8. Open a Pull Request if collaborating.
9. Merge after review.

---

# Best Practices

- Follow consistent coding standards.
- Write reusable and modular code.
- Handle errors appropriately.
- Document important functionality.
- Avoid hardcoded values whenever possible.
- Keep dependencies up to date.
- Maintain a clean Git history.

---

# AI Assistant Guidelines

When using Claude Code or another AI assistant:

- Follow the coding conventions in this document.
- Preserve the existing project structure.
- Prefer simple and maintainable solutions.
- Explain significant changes before implementing them.
- Do not modify unrelated files.
- Update documentation when adding new features.
- Use Conventional Commits for suggested commit messages.

---

# Documentation

Whenever new features are added:

- Update the README if necessary.
- Keep setup instructions accurate.
- Document any new dependencies or configuration.

---

This document should evolve as the project grows and new technologies or conventions are adopted.
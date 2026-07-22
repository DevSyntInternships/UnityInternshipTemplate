# GitHub Submission Guidelines

Welcome to the DevSynt Game Development Internship.

These guidelines define the GitHub workflow and coding standards that every intern must follow throughout the internship.

---

# Repository Workflow

Do not work directly on the `main` branch.

Before starting any weekly assignment, create your own feature branch using the following naming convention:

```bash
git checkout -b feature/<your-github-username>/week<number>
```

Example:

```bash
git checkout -b feature/johnsmith/week1
```

All development must be done on your own feature branch.

---

# Before Submitting

Before creating a Pull Request, ensure that:

- The Unity project opens without errors.
- The project compiles successfully.
- The folder structure is maintained.
- Scripts are placed in the correct folders.
- Unused assets have been removed.
- Your code is clean, readable, and well-organized.

---

# Commit Messages

Use meaningful commit messages.

Good Examples

```
Initialize Unity Project

Implement Player Controller

Add Rigidbody Physics

Complete Week 1 Unity Foundations
```

Avoid

```
Update

Done

Final

abc
```

---

# Pull Requests

Every weekly assignment must be submitted through a Pull Request.

Do not merge your own Pull Request.

Wait for your mentor to review your submission before making any further changes.

---

# Coding Standards

Follow these coding conventions:

- Use PascalCase for classes and methods.
- Use camelCase for variables.
- Keep methods short and focused.
- Avoid unnecessary comments.
- Organize your scripts logically.
- Write clean, maintainable code.

---

# Folder Rules

Maintain the provided folder hierarchy.

Scripts

```
Assets/Scripts
```

Scenes

```
Assets/Scenes
```

Prefabs

```
Assets/Prefabs
```

Materials

```
Assets/Materials
```

Never create unnecessary folders or move project files without permission.

---

# Branch Naming Convention

Every intern must create a unique branch for each week's assignment.

Examples

```
feature/johnsmith/week1

feature/johnsmith/week2

feature/johnsmith/week3
```

Do not reuse old branches for new assignments.

---

Thank you for following these guidelines and maintaining a professional development workflow.

**DevSynt Game Development Team**

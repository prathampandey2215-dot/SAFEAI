Coding Standards

Project

SafeAI – AI Powered Cybersecurity Platform

---

Purpose

This document defines the coding standards and development guidelines for the SafeAI project. Following these standards ensures the codebase remains clean, consistent, secure, and maintainable.

---

General Principles

- Write clean and readable code.
- Keep functions small and focused.
- Avoid duplicate code.
- Prefer simplicity over unnecessary complexity.
- Write self-explanatory code whenever possible.

---

Naming Conventions

Files

- Use lowercase letters.
- Separate words with underscores.

Examples:

- login_screen.dart
- dashboard_screen.dart
- security_service.dart

---

Classes

Use PascalCase.

Examples:

- LoginScreen
- SecurityService
- UserProfile

---

Variables

Use camelCase.

Examples:

- userName
- securityScore
- currentUser

---

Constants

Use UPPER_SNAKE_CASE.

Examples:

- MAX_RETRY_COUNT
- API_TIMEOUT

---

Folder Structure

Group files by feature instead of file type whenever practical.

Example:

- auth/
- dashboard/
- scanner/
- settings/
- shared/

---

Functions

Functions should:

- Perform one clear task.
- Use descriptive names.
- Return meaningful results.
- Handle errors gracefully.

---

Comments

Use comments to explain why, not what.

Avoid unnecessary comments that repeat the code.

---

Error Handling

- Validate all user input.
- Handle exceptions safely.
- Display user-friendly error messages.
- Log unexpected errors appropriately.

---

Security Guidelines

- Never hardcode passwords or API keys.
- Validate all external input.
- Use secure communication (HTTPS).
- Protect sensitive user data.
- Follow the principle of least privilege.

---

Git Commit Messages

Use clear commit prefixes.

Examples:

- feat: Add QR scanner
- fix: Resolve login issue
- docs: Update API documentation
- refactor: Improve AI service
- test: Add dashboard tests
- chore: Update dependencies

---

Branch Strategy

- main
- develop
- feature/*
- bugfix/*
- release/*

---

Testing

Before submitting code:

- Ensure the project builds successfully.
- Verify new functionality.
- Check for regressions.
- Review code for readability.

---

Dependencies

- Use trusted packages only.
- Keep dependencies updated.
- Remove unused packages.

---

Documentation

Every major feature should include:

- Code documentation
- User documentation
- Update to CHANGELOG.md (if applicable)

---

Code Review Checklist

Before merging:

- Code follows project standards.
- No sensitive information is included.
- Errors are handled correctly.
- Documentation is updated.
- Tests pass successfully.

---

Conclusion

Following these coding standards helps maintain a high-quality, secure, and scalable codebase for SafeAI throughout its development lifecycle.
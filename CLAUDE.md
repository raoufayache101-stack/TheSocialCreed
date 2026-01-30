# CLAUDE.md — TheSocialCreed

This file provides guidance for AI assistants (and developers) working on the TheSocialCreed project.

## Project Overview

**TheSocialCreed** is a new project. The repository was initialized but does not yet contain application code, configuration, or documentation beyond this file. This document will evolve as the project takes shape.

## Repository Status

- **State:** Freshly initialized (no application code yet)
- **Branch strategy:** Feature branches prefixed with `claude/` for AI-assisted development
- **Remote:** Configured via local proxy

## Development Conventions

### Git Workflow

- Create feature branches from the main branch
- Use clear, descriptive commit messages that explain *why*, not just *what*
- Never force-push to shared branches
- Keep commits focused — one logical change per commit

### Branch Naming

- AI-assisted branches: `claude/<descriptor>-<session-id>`
- Feature branches: `feature/<short-description>`
- Bug fixes: `fix/<short-description>`

### Code Style (to be established)

Once the tech stack is chosen, add:
- Linter configuration (ESLint, Pylint, etc.)
- Formatter configuration (Prettier, Black, etc.)
- Editor configuration (`.editorconfig`)

### File Organization (to be established)

Standard conventions to follow once the project structure is created:
- Keep source code in a `src/` directory
- Keep tests alongside source files or in a dedicated `tests/` directory
- Store configuration at the project root
- Use a `.gitignore` appropriate for the chosen stack
- Never commit secrets, credentials, or `.env` files

## For AI Assistants

### Before Making Changes

1. Read existing code before modifying it
2. Check for established patterns and follow them
3. Run any existing tests before and after changes
4. Review `package.json` (or equivalent) for available scripts

### Key Principles

- **Minimal changes:** Only modify what is necessary for the task
- **No over-engineering:** Avoid abstractions, helpers, or features not explicitly requested
- **Security first:** Never introduce vulnerabilities (XSS, injection, etc.)
- **No secrets in code:** Use environment variables for sensitive configuration
- **Preserve conventions:** Follow existing code style and patterns in the repo

### Common Commands (to be updated)

Once the project has a build system, document:
```
# Install dependencies
# Run development server
# Run tests
# Build for production
# Lint / format
```

## Architecture (to be defined)

This section should be updated once the tech stack and architecture are chosen. Include:
- Framework and language choices
- Database and ORM
- Authentication strategy
- API design (REST, GraphQL, etc.)
- Deployment target (cloud provider, containerization, etc.)
- Third-party service integrations

## Environment Setup (to be defined)

Once dependencies exist, document:
- Required runtime versions (Node.js, Python, etc.)
- Environment variable requirements
- Local development prerequisites
- Database setup instructions

---

*This file should be kept up to date as the project evolves. Every significant architectural decision or workflow change should be reflected here.*

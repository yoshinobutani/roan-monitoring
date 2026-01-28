# CLAUDE.md - AI Assistant Guidelines

## Project Overview

**Repository:** roan-monitoring
**Status:** Early-stage / Initialization
**Primary Language:** Not yet determined (repository contains no source code)

This repository appears to be in its initial stages. The name "roan-monitoring" suggests it may be intended as a monitoring system or tool, but no implementation exists yet.

## Current Repository State

### Directory Structure
```
roan-monitoring/
├── README.md          # Currently contains personal notes (not project documentation)
├── CLAUDE.md          # This file - AI assistant guidelines
└── .git/              # Git version control
```

### What Exists
- Basic git repository with version control
- README.md file (contains personal notes in Japanese, not technical documentation)

### What Does NOT Exist
- No source code files
- No configuration files (package.json, requirements.txt, etc.)
- No build/test/deploy scripts
- No CI/CD pipeline
- No .gitignore file
- No proper project documentation

## Development Guidelines for AI Assistants

### General Principles

1. **Ask Before Assuming**: Since this is an early-stage project with no defined tech stack, always confirm with the user what language/framework they want to use before creating files.

2. **Start Simple**: When implementing features, start with minimal viable implementations rather than complex architectures.

3. **Document As You Go**: Add appropriate documentation and comments when creating new code.

4. **Follow Standard Conventions**: When a tech stack is chosen, follow the standard conventions for that ecosystem.

### Git Workflow

1. **Branch Naming**: Claude branches follow the pattern `claude/claude-md-{session-id}`
2. **Commit Messages**:
   - Use clear, descriptive commit messages
   - The repository has used both English and Japanese commits
   - Follow conventional commits format when adding new code: `feat:`, `fix:`, `docs:`, `chore:`
3. **Push Commands**: Always use `git push -u origin <branch-name>`

### Code Style (When Applicable)

Since no code exists yet, when implementing:

**For JavaScript/TypeScript:**
- Use ES6+ syntax
- Prefer async/await over callbacks
- Use meaningful variable and function names

**For Python:**
- Follow PEP 8 style guidelines
- Use type hints where appropriate
- Prefer f-strings for string formatting

**For Any Language:**
- Keep functions small and focused
- Write self-documenting code with clear naming
- Add comments only for complex logic

### File Organization Recommendations

When building out this project, consider:

```
roan-monitoring/
├── src/               # Source code
├── tests/             # Test files
├── docs/              # Documentation
├── scripts/           # Build/deploy scripts
├── config/            # Configuration files
├── README.md          # Project documentation
├── CLAUDE.md          # AI assistant guidelines
├── .gitignore         # Git ignore rules
└── [package file]     # package.json, requirements.txt, etc.
```

## Important Notes

### Current README Content
The README.md currently contains personal notes in Japanese rather than project documentation. When the project develops further, this should be updated to include:
- Project description and purpose
- Installation instructions
- Usage examples
- Contributing guidelines

### No Dependencies
This project has no dependencies defined. When adding dependencies:
- Use a package manager appropriate for the chosen language
- Pin versions for reproducibility
- Document any system requirements

### No Tests
No testing framework is configured. When adding tests:
- Set up an appropriate testing framework
- Aim for meaningful test coverage
- Include both unit and integration tests where applicable

## Quick Reference

| Aspect | Current State |
|--------|---------------|
| Language | Not defined |
| Framework | Not defined |
| Package Manager | Not defined |
| Testing | Not configured |
| CI/CD | Not configured |
| Documentation | Minimal |

## Commands (To Be Added)

When the project is set up, common commands should be documented here:

```bash
# Install dependencies
# [to be defined]

# Run development server
# [to be defined]

# Run tests
# [to be defined]

# Build for production
# [to be defined]
```

---

*Last updated: 2026-01-28*
*This file should be updated as the project evolves.*

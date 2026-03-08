# CLAUDE.md - AI Assistant Guide

This document provides guidance for AI assistants working on this repository.

## Project Overview

**Project**: neuro-ip.network
**Repository**: gaycowboy.work
**License**: GPL v3
**Status**: Early-stage project scaffold

This repository is for neuro-ip.network projects. It is currently in its initial setup phase with minimal structure.

## Repository Structure

```
gaycowboy.work/
├── LICENSE          # GNU General Public License v3
├── README.md        # Project title and description
├── config.toml      # Configuration file (placeholder)
└── CLAUDE.md        # This file - AI assistant guide
```

## Current State

This is a nascent project with:
- Basic licensing (GPL v3) established
- Minimal documentation
- Empty configuration placeholder
- No build system or dependencies defined yet

## Development Guidelines

### Git Workflow

- **Branch naming**: Use pattern `<tool>/<description>-<id>` (e.g., `claude/add-feature-ABC123`)
- **Commits**: Use clear, descriptive commit messages
- **Signed commits**: Repository uses SSH key signing
- **Push command**: Always use `git push -u origin <branch-name>`

### License Compliance

All code contributions must comply with **GPL v3**:
- Source code must be made available
- Derivative works must use the same license
- Include license headers in source files when appropriate

### Configuration

- Configuration uses TOML format (`config.toml`)
- Keep configuration separate from code

## Priorities for Development

Since this is an early-stage project, AI assistants should consider:

1. **Documentation**: Expand README.md with project details, setup instructions, and usage examples
2. **Project Definition**: Help define the technology stack and project type
3. **Build System**: Establish build, test, and deployment workflows as the project grows
4. **Configuration**: Define config.toml structure based on project needs
5. **CI/CD**: Consider automated testing and deployment when appropriate

## CloudCannon Integration

Based on commit history, this project may integrate with CloudCannon CMS. Be aware of:
- Potential static site generation requirements
- Content management workflows
- CloudCannon-specific configuration needs

## Commands Reference

Currently no build commands are defined. As the project develops, add commands here:

```bash
# Placeholder - add project-specific commands as they are established
```

## Notes for AI Assistants

- This project is in its earliest stages - help establish patterns and conventions
- Ask clarifying questions when project direction is unclear
- Prioritize documentation to help future contributors
- Follow GPL v3 requirements for any code contributions
- Keep changes focused and avoid over-engineering

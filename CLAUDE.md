# CLAUDE.md - AI Assistant Guide for neuro-ip.network

This document provides guidance for AI assistants working with the neuro-ip.network repository.

## Project Overview

**Project Name:** neuro-ip.network
**License:** GNU General Public License v3 (GPL-3.0)
**Status:** Early development / Template repository
**CMS Platform:** CloudCannon
**Static Site Generator:** Hugo (planned)

This repository hosts the neuro-ip.network projects, managed through CloudCannon CMS with Hugo as the intended static site generator.

## Repository Structure

```
gaycowboy.work/
├── README.md        # Project description
├── LICENSE          # GPL v3 license
├── config.toml      # Hugo configuration (currently empty)
└── CLAUDE.md        # This file - AI assistant guidance
```

### Current State

The repository is in a pre-development stage with minimal files:
- **README.md** - Basic project title and description
- **LICENSE** - Full GPL v3 license text
- **config.toml** - Empty Hugo configuration placeholder

## Development Workflow

### Git Branching

- **master** - Main stable branch
- Feature branches should follow the pattern: `feature/<description>` or `claude/<description>-<id>`

### Git Commands

```bash
# Check status
git status

# Stage changes
git add <specific-files>

# Commit (always use descriptive messages)
git commit -m "Type: Brief description of changes"

# Push to remote
git push -u origin <branch-name>
```

### Commit Message Conventions

Use descriptive commit messages with a type prefix:
- `Add:` - New files or features
- `Update:` - Modifications to existing content
- `Fix:` - Bug fixes or corrections
- `Remove:` - Deleted files or features
- `Docs:` - Documentation updates

Example: `Add: Homepage content and navigation structure`

## Hugo Static Site Setup (Planned)

When the site is set up, the expected structure will be:

```
gaycowboy.work/
├── config.toml         # Hugo site configuration
├── content/            # Markdown content files
│   ├── _index.md      # Homepage content
│   └── pages/         # Additional pages
├── layouts/            # HTML templates
│   ├── _default/      # Default templates
│   └── partials/      # Reusable template parts
├── static/             # Static assets (images, CSS, JS)
├── themes/             # Hugo themes (if using)
├── data/               # Data files (YAML, JSON, TOML)
└── assets/             # Files processed by Hugo Pipes
```

### Hugo Commands (When Configured)

```bash
# Start development server
hugo server -D

# Build site for production
hugo

# Create new content
hugo new content/<path>/filename.md
```

## CloudCannon Integration

This project uses CloudCannon as a Git-based CMS. Key points:
- Content changes may be made through the CloudCannon interface
- Changes are committed directly to Git
- Commit messages from CloudCannon follow the format: "Added/Updated X file(s) via CloudCannon"

## AI Assistant Guidelines

### When Working on This Repository

1. **Respect the GPL v3 License** - All contributions must be compatible with GPL v3
2. **Keep Changes Minimal** - Only make changes directly requested
3. **Use Descriptive Commits** - Follow the commit message conventions above
4. **Preserve CloudCannon Compatibility** - Don't break CMS integration
5. **Document Changes** - Update relevant documentation when making structural changes

### File Handling

- **Never modify LICENSE** without explicit permission
- **Update README.md** when adding significant features
- **Use config.toml** for Hugo configuration following Hugo's documentation
- **Create content in Markdown** following Hugo front matter conventions

### Hugo Content Front Matter Template

When creating new content files:

```markdown
---
title: "Page Title"
date: YYYY-MM-DD
draft: false
description: "Brief page description"
---

Content goes here...
```

### Things to Avoid

- Don't introduce dependencies without explicit approval
- Don't add CI/CD configuration unless requested
- Don't create unnecessary build tooling
- Don't add IDE-specific configuration files
- Don't commit secrets, API keys, or sensitive data

## Useful Resources

- [Hugo Documentation](https://gohugo.io/documentation/)
- [CloudCannon Hugo Docs](https://cloudcannon.com/documentation/guides/hugo-starter-guide/)
- [GPL v3 License](https://www.gnu.org/licenses/gpl-3.0.en.html)
- [CommonMark Markdown Spec](https://commonmark.org/)

## Contact

For questions about this project, refer to the repository owner (Pup Ragnarok).

---

*Last updated: 2026-02-01*

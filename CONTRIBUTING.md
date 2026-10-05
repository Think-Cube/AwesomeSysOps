# Contributing to Awesome SysOps

Thank you for your interest in contributing! This document describes how to add or update entries in this curated list.

## Quality Standards

All submissions must meet these criteria:

- **Actively maintained** — last commit within 12 months or is a stable, widely-used project.
- **Well documented** — has a README, docs site, or clear description.
- **Widely used or noteworthy** — significant GitHub stars, user base, or strong niche use case.
- **Production ready** — not a toy project or early alpha.
- **SysOps-focused** — directly relevant to system administration and operations.

## How to Add an Entry

1. **Fork** this repository.
2. **Create a branch**: `git checkout -b add/tool-name`
3. **Edit `README.md`**:
   - Add the entry to the most appropriate category, in alphabetical order within the section.
   - Use this format:
     ```markdown
     * [Tool Name](https://link-to-docs-or-github.com/) – one sentence description starting with a lowercase letter, ending with a period.
     ```
   - Keep descriptions concise (under 120 characters).
   - Link to official documentation, not GitHub, when a docs site exists.
4. **Open a Pull Request** using the PR template.

## PR Checklist

- [ ] Entry is in alphabetical order within its section.
- [ ] Description starts with a lowercase letter and ends with a period.
- [ ] Link goes to official docs or GitHub (not a blog post or mirror).
- [ ] No duplicate entry exists.
- [ ] The tool is not deprecated or abandoned.
- [ ] PR title follows the format: `Add: ToolName` or `Update: ToolName` or `Remove: ToolName`.

## Removing an Entry

Open an issue using the **Remove Resource** template explaining why the entry should be removed (abandoned, deprecated, security vulnerability, etc.).

## Code of Conduct

By contributing, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

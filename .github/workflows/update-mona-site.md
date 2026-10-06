---
name: Update Mona's GitHub Info Website
on:
  workflow_dispatch:
---

# Purpose
Automate updates to Mona's GitHub Info website by referencing notes and release details.

# Allowed File Modifications
- Files in the `site/` directory only.

# Information Sources
1. **Mona's Notes**: Consult files in the `notes/` directory.
2. **GitHub Blog**: Check recent blog announcements.
3. **GitHub Changelog**: Check recent changelog entries.

# Instructions & Expected Output
1. Read Mona's notes to understand current site context.
2. Review recent updates from the GitHub Blog and Changelog.
3. Propose updates to files inside the `site/` directory.
4. Open a Pull Request with the proposed site updates and include a clear summary of changes and sources used.
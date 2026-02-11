# GitHub Actions Workflows Lab

## Workflow 1 – Dependent Jobs
This workflow runs when code is pushed to the main branch.

It demonstrates job dependencies using the needs keyword.

Execution Order:
Build → Test → Deploy

Key Concepts:
- needs: Controls job order
- runs-on: Selects runner OS


## Workflow 2 – Multi Platform Workflow
This workflow runs when a Pull Request is created.

It runs jobs in parallel on:
- Ubuntu
- Windows
- macOS

Key Concepts:
- runs-on: Selects operating system
- Parallel execution improves testing speed


## Challenges Faced
- Git authentication issues solved using token login
- YAML formatting errors fixed by correcting indentation

---
on:
  issues:
    types: [opened]

permissions:
  issues: write

tools:
  github:
    toolsets: [issues]
---

# Workflow Description

Read the issue #${{ github.event.issue.number }}. Add a comment to the issue listing useful resources and links.

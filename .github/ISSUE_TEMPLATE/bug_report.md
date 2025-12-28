---
name: "🐛 Bug Report"
description: Report a bug to help improve the portfolio
title: "[BUG] "
labels: ["bug"]
assignees: [vijayshikhare]
body:
  - type: markdown
    attributes:
      value: "Thanks for reporting! Please fill below."
  - type: textarea
    id: description
    attributes:
      label: "Describe the Bug"
      description: "What went wrong? Include screenshots if possible."
      placeholder: "e.g., Animation breaks on mobile..."
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: "Steps to Reproduce"
      description: "How can I trigger this?"
      placeholder: "1. Go to Skills section 2. Hover card 3. See error"
    validations:
      required: true
  - type: dropdown
    id: browsers
    attributes:
      label: "Browser"
      options:
        - Chrome
        - Firefox
        - Safari
        - Edge
    validations:
      required: true
  - type: textarea
    id: additional
    attributes:
      label: "Additional Context"
      placeholder: "OS, device, etc."

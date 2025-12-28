---
name: "🚀 Feature Request"
description: Suggest a new feature or improvement
title: "[FEAT] "
labels: ["enhancement"]
assignees: [vijayshikhare]
body:
  - type: markdown
    attributes:
      value: "Love a new idea? Let's discuss!"
  - type: textarea
    id: description
    attributes:
      label: "Feature Description"
      description: "What would you like added?"
      placeholder: "e.g., Add blog section..."
    validations:
      required: true
  - type: textarea
    id: benefits
    attributes:
      label: "Why This Feature?"
      placeholder: "How does it help users/contributors?"
    validations:
      required: true
  - type: textarea
    id: implementation
    attributes:
      label: "Implementation Ideas"
      placeholder: "Any tech suggestions?"

name: Bug Report
description: Report a bug to help us improve
title: "[BUG] "
labels: ["bug"]

body:
  - type: markdown
    attributes:
      value: |
        Thank you for reporting a bug! Please fill in the details below.

  - type: textarea
    attributes:
      label: Description
      description: Clear and concise description of the bug
      placeholder: What is the issue?
    validations:
      required: true

  - type: textarea
    attributes:
      label: Steps to Reproduce
      description: Steps to reproduce the behavior
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. See error
    validations:
      required: true

  - type: textarea
    attributes:
      label: Expected Behavior
      description: What should happen instead?
      placeholder: Describe what you expected to happen

  - type: textarea
    attributes:
      label: Actual Behavior
      description: What actually happened?
      placeholder: Describe what actually happened

  - type: input
    attributes:
      label: Browser
      description: Which browser are you using?
      placeholder: e.g., Chrome 120, Firefox 121, Safari 17
    validations:
      required: true

  - type: input
    attributes:
      label: Device
      description: Device information
      placeholder: e.g., Windows 11, macOS 14, iPhone 15
    validations:
      required: true

  - type: textarea
    attributes:
      label: Screenshots
      description: Add screenshots if applicable
      placeholder: Drag and drop images here

  - type: textarea
    attributes:
      label: Additional Context
      description: Any other information that might help
      placeholder: Add any other context about the problem here

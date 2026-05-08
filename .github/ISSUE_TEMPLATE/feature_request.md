name: Feature Request
description: Suggest a new feature or enhancement
title: "[FEATURE] "
labels: ["enhancement"]

body:
  - type: markdown
    attributes:
      value: |
        Thank you for suggesting an enhancement! Please fill in the details below.

  - type: textarea
    attributes:
      label: Description
      description: Describe the feature or enhancement you'd like to see
      placeholder: What would you like to see added or improved?
    validations:
      required: true

  - type: textarea
    attributes:
      label: Problem Statement
      description: What problem does this feature solve?
      placeholder: Describe the problem or use case
    validations:
      required: true

  - type: textarea
    attributes:
      label: Proposed Solution
      description: How would you like this feature to work?
      placeholder: Describe your proposed solution

  - type: textarea
    attributes:
      label: Alternative Solutions
      description: Are there alternative approaches?
      placeholder: Describe any alternative approaches you've considered

  - type: textarea
    attributes:
      label: Additional Context
      description: Any other information or context
      placeholder: Screenshots, mockups, or other examples are welcome

  - type: checkboxes
    attributes:
      label: Checklist
      options:
        - label: I've checked if this feature already exists
          required: true
        - label: I've searched existing issues for similar requests
          required: true

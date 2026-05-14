---
name: Custom Issue
about: General purpose issue template
title: "[CUSTOM] <title>"
labels:
  - needs-triage
body:
  - type: textarea
    id: description
    attributes:
      label: Describe the issue
      description: |
        Provide information about your issue here.

        NOTE: Before submitting, please search for duplicate or closed issues.
    validations:
      required: true
---

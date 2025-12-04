---
name: Bug Report
about: "Create a report to help us improve"
title: "Bug: [Describe the bug here]"
labels: "bug"
assignees:
  - "chirag127"
body:
  - type: markdown
    attributes:
      value: |-
        ## Thank you for reporting a bug!

        Please provide as much detail as possible to help us diagnose and fix the issue.

        **Archived Repository Notice:**
        This repository is **archived** and no longer actively maintained. While we appreciate bug reports for historical context, active development and fixes are not expected.

        **Project:** `Archived-TubeScout-YouTube-Scraping-And-Search-Python-Library`
        **Repository:** [https://github.com/chirag127/Archived-TubeScout-YouTube-Scraping-And-Search-Python-Library](https://github.com/chirag127/Archived-TubeScout-YouTube-Scraping-And-Search-Python-Library)

        --- 
  - type: input
    id: "version"
    attributes:
      label: "Library Version"
      description: "What version of the library are you using? If unsure, try to check the installed version or commit hash."
      placeholder: "e.g., 1.0.0 or specific commit hash"
    validations:
      required: true
  - type: input
    id: "os"
    attributes:
      label: "Operating System"
      description: "What OS are you experiencing the bug on?"
      placeholder: "e.g., macOS 13.5, Ubuntu 22.04, Windows 11"
    validations:
      required: true
  - type: input
    id: "python_version"
    attributes:
      label: "Python Version"
      description: "What version of Python are you using?"
      placeholder: "e.g., Python 3.9.16"
    validations:
      required: true
  - type: textarea
    id: "description"
    attributes:
      label: "Bug Description"
      description: "Provide a clear and concise description of the bug. What happened? What did you expect to happen?"
      placeholder: "A detailed explanation of the issue..."
    validations:
      required: true
  - type: textarea
    id: "steps_to_reproduce"
    attributes:
      label: "Steps to Reproduce"
      description: "Provide detailed steps to reproduce the behavior. Please be specific."
      placeholder: "1. Go to '...'
2. Click on '...'
3. Observe the error..."
    validations:
      required: true
  - type: textarea
    id: "error_message"
    attributes:
      label: "Error Message (if any)"
      description: "If applicable, please paste the full error message or stack trace here."
      placeholder: "
[Paste error here]
"
    validations:
      required: false
  - type: textarea
    id: "logs"
    attributes:
      label: "Relevant Logs (if any)"
      description: "Attach any relevant logs that might help in debugging."
      placeholder: "
[Paste logs here]
"
    validations:
      required: false
  - type: textarea
    id: "additional_context"
    attributes:
      label: "Additional Context"
      description: "Add any other context about the problem here. Screenshots are also helpful."
      placeholder: "Any other information that you think is relevant..."
    validations:
      required: false

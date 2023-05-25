name: 🐛 Bug report
description: Create a report to help us improve
labels: [bug]
body:
  - type: textarea
    attributes:
      label: ℹ️ System information
      description: |
        You can find the Dropshelf version number by right-clicking on the Dropshelf tray icon and going to <kbd>Settings > About Dropshelf</kbd>.
        You can find your Windows version by pressing <kbd>Win</kbd> + <kbd>Pause/Break</kbd> or by pressing <kbd>Win</kbd> + <kbd>R</kbd> and running <kbd>winver</kbd>.
      value: |
        - Dropshelf version: 
        - Windows version and OS build: 
      placeholder: |
        - Dropshelf version: e.g. Version 1.0.0
        - Windows version and OS build: e.g. Windows 11 21H2 (OS Build 22000.194)
      render: Markdown
    validations:
      required: true
  - type: textarea
    attributes:
      label: 📝 Description
      description: A clear description of what the bug is.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Steps to reproduce
      description: We highly suggest including screenshots wherever possible.
      placeholder: |
        e.g.
        1. Go to '....'
        2. Click on '....'
        3. Scroll down to '....'
        4. See the error
    validations:
      required: false

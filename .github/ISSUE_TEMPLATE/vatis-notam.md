name: vATIS Profile Update
description: Request an update to a vATIS profile
title: "[vATS]: "
labels: ["enhancement"]
body:
  - type: dropdown
    id: type
    attributes:
      label: What type of vATIS Update are you requesting?
      description: Please select the appropriate type of vATIS update.
      multiple: false
      options:
        - New Runway Configuration
        - New NOTAM
        - New Airport
        - Other
    validations:
      required: true
  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context (Optional)
      description: Add any other context or screenshots about the feature request here.
    validations:
      required: false

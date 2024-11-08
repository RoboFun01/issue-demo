name: NOTAM
description: Suggest a NOTAM Implementation to this Sector File
title: "[NOTAM]: "
labels: ["enhancement"]
body:
  - type: textarea
    id: applicable-notam
    attributes:
      label: Applicable NOTAM
      description: Please provide the NOTAM ID for this request.
    validations:
      required: true
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Please provide the NOTAM description.
    validations:
      required: true
  - type: checkboxes
    id: notam-impact
    attributes:
      label: What features does this NOTAM impact?
      description: What should all be updated in the sector files?
      options:
        - label: Ground Layout
          required: false
        - label: GroundRadar
          required: false
        - label: TopSky
          required: false
        - label: vATIS
          required: false
      validations:
        required: true
  - type: checkboxes
    id: eaip-impact
    attributes:
      label: What eAIP pages require updating?
      description: What pages needs to be updated?
      options:
        - label: Airspace
          required: false
        - label: AD Delivery
          required: false
        - label: AD Ground
          required: false
        - label: AD Tower
          required: false
        - label: AD Approach
          required: false
      validations:
        required: true
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots
      description: If possible, attach screenshots that demonstrate the need.
    validations:
      required: false
  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context (Optional)
      description: Add any other context about the ground layout request here.
    validations:
      required: false

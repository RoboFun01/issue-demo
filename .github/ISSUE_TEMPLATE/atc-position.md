name: ATC Position
description: Request a new or a change to an ATC Position
title: "[PSTN]: "
labels: ["enhancement"]
body:

  - type: textarea
    id: applicable-position
    attributes:
      label: Describe the bug
      description: A clear and concise description of what the bug is and what needs to be fixed.
    validations:
      required: true
## Applicable Postion

Please provide the applicable position for this request. Example: FNAN_GND or GOOO_FSS

## What features does this NOTAM impact?

- [ ] New Position
- [ ] Retire Position
- [ ] New Frequency
- [ ] Other

## Additional context

Add any other context about the ground layout request here.

## ATC Position Checklist

- [ ] Aeronav GNG
- [ ] Audio for VATSIM
- [ ] TopSky (Settings, Maps, CPDLC)
- [ ] GroundRadar (Maps)
- [ ] SSA Website
- [ ] SSA ATC Position Registry

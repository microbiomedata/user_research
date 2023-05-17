---
name: User Research Request
about: Describe this issue template's purpose here.
title: "[User Research Request]"
labels: ''
assignees: ljohnson09

---

name: User Research Request
description: File a request for User Research
title: "[User Research] <title>"
labels: [user_research]
body:
- type: textarea
  attributes:
    label:user research
    description: Please provide a description of the information you would like/goals for your request. (Ex We would like usability testing of x features on the submission portal; beta-testing of x workflow in NMDC EDGE. This will help us achieve or understand  ___. )
  validations:
    required: false- type: checkboxes
  attributes:
    label: Is there an existing issue for this?
    description: Please search to see if an issue already exists for this request:
    - label: I have searched the existing issues
      required: true
 - type: checkboxes
    id: products
    attributes:
      label:
      description: Select the NMDC product related to your request
      options:
        - label: Submission Portal
        - label: Data Portal
        - label: EDGE
        - label: API
        - label: Other

 - type: checkboxes
    id: priority
    attributes:
      label:
      description: Identify the level of priority for testing
        - label: Low (nice to have)
        - label: Medium
        - label: High
        - label: Very High (required info to move forward with product)
          
- type: textarea
  attributes:
    label: 
    description: potential interview candidates
    required: false
- type: textarea
  attributes:
    label: Interview candidates
    description:Please refer potential interview candidates at https://docs.google.com/spreadsheets/d/1YNUOFFsagIGJEx2ru4_FpEroInhnEl5MCQmYymP6CTg/edit#gid=0 :
    required: false

- type: textarea
  attributes:
    label: Team members
    description: Identify which team members should be looped in for script/task review
 
  validations:
    required: false

- type: textarea
  attributes:
    label: Team members
    description: Identify which team members should be looped in for insights/actions prioritization and implementation
 
  validations:
    required: false

name: Feature request
about: Request a new feature to be added to the site!
title: "*Feature request title here*"
labels: Suggestion
assignees: ''
body:
  - type: input
    attributes:
      label: What would you like to add?
      description: (stop asking me to add new versions, i'll do that in my own time.)
      placeholder: Something cool!
  - type: textarea
    attributes:
      label: How would you like this to be implemented? (optional)
      description: You can tell me how you would like me to make this if there is a preferred way.
      placeholder: Put on some sunglasses and do a dance!
    validations:
      required: false
  - type: textarea
    attributes:
      label: Any additional context: (optional)
    validations:
      required: false

---
formName: enquiry
honeyPot: sirname
action: /thank-you
submitButton: Send Enquiry
input:
  - inputName: name
    type: field
    input label: What’s your name?
    inputRequired: true
  - inputName: sirname
    type: hidden_field
    input label: sirname
  - inputName: program selected (hidden from user)
    type: hidden_field
    input label: program
  - inputName: email
    type: field
    input label: What’s your email address?
    inputRequired: true
    input Pattern: "[^@]+@[^\\.]+\\..+"
  - inputName: phone
    type: field
    input label: What’s the best number to contact you on?
    inputRequired: true
    inputData: "+61"
  - inputName: time
    type: select
    input label: When is the best time to contact you?(Melbourne Time)
    options:
      - value: 7am-9am
      - value: 9am-12pm
      - value: 12pm-3pm
      - value: 3pm-6pm
      - value: 7pm-10pm
  - inputName: goals
    type: textArea
    input label: What are some career goals you want to achieve?
    spellcheck: true
---

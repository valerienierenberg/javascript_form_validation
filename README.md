# JavaScript Form Validation

- This project is a modern JavaScript Form validator coded from scratch.
- View and test my validator out for yourself [here (Deployed with GitHub Pages)](https://valerienierenberg.github.io/javascript_form_validation/)

## Features

- Fields: ```username```, ```email```, ```password```, and ```re-typed password```
- Validates that all fields are not left empty
- Appropriate error messages are displayed if any field is left empty
- Further validations:
    - Email:
        - Regex used to determine whether or not a valid email is entered.
        - Appropriate error message displayed if input email is invalid
    - Re-typed password:
        - If re-typed password does not match original password, appropriate error message is displayed
- Error or success classes are added to elements, and respective icons are displayed depending on whether or not the field was entered correctly


## Demo of Form Validator with Errors/Successes

![Form Validation gif](./formvalidationgif.gif)

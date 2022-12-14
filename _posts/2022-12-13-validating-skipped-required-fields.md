# Validating **Skipped** required fields

### Objective: 
Most forms show required error messages when the user moves out of a required field or submits the form.  The [right time](https://designmodo.com/ux-form-validation/#right-time) to show errors is when a user skips a required field.  A field is **skipped** whenever any control below the required field is used.  




### Example:
The user's only interaction is clicking the 3rd field, the first two fields should display the "<font color="red">Required</font>" error messages. 

![Example](https://raw.githubusercontent.com/afrievalt/afrievalt.github.io/main/docs/assets/past-validation.gif)

[Try it Live in code sandbox](https://codesandbox.io/s/react-final-form-jit-validation-1140sv)
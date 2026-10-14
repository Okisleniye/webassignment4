# Assignment 4. Forms and Validation

Name: Fariddin

Group: 4

All tasks are in one file, index.html. Each task has its own section on the page.

## Part 1. Basic HTML Forms

### Task 0. Simple Contact Form

Create a basic contact form with name, email, message and a submit button. All fields have labels.


### Task 1. Form with HTML5 Validation

Add built-in validation attributes (required, type, minlength, maxlength) and test how the browser checks the fields.

Empty field:


Wrong email:


## Part 2. Bootstrap Forms

### Task 2. Bootstrap Form Styling

Recreate the contact form with Bootstrap form classes, arrange the fields with the grid, add placeholders and helper text.


### Task 3. Bootstrap Validation Styles

Use is-valid and is-invalid classes and show feedback messages under the inputs. Test with valid and invalid data.

Invalid data:


Valid data:


## Part 3. Advanced Form Project

### Task 4. Registration Form

Registration form with first name, last name, email, password and confirm password, gender (radio buttons), hobbies (checkboxes), country (select), submit and reset buttons. The form is responsive with the Bootstrap grid, uses HTML5 validation and Bootstrap validation feedback.

Empty form:


Errors:


Success:


Mobile:


## Summary

First I made a simple form with labels in task 0 and added the validation attributes in task 1. Then I rebuilt the form with Bootstrap classes and the grid in task 2. In task 3 I used JavaScript with checkValidity() to add the is-valid and is-invalid classes and show the feedback messages. In the last task I combined everything in a registration form. Bootstrap shows the messages with the was-validated class, and a small script checks that both passwords are the same.

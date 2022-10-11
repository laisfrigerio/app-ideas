# Multistep Form

**Tier:** 2-Intermediate

Multistep forms are a really common problem that developers need to solve in Front-end projects. Actually that is no so easy to make, but if you know how manage states and contexts you can do it better.

The goal of the Multistep Form app is demonstrate how to create custom form with multiple steps and states and contexts management.

## User Stories

-  User can see 3 steps with diferent types of fields, include text area, checkbox, combobox, radio button and more. All the fields are required and should be validate using the most usual rules with regEx or libs. 

- In the first step in the bottom of form user can see 1 button (next), the expected behavior is when click in the next button can see the next step, but this button should be disabled and just enable when all the fields are filled correctly.

- In the second step in the bottom of form user can see 2 buttons (back and next), the expected behavior is when click in the next button user can see the next step, but this button should be disabled and just enable when all the fields are filled correctly. And when user click in the back button can see the first step.

- In the last step user can see 2 buttos (back and submit), the expected behavior is when user click in the submit button can see the modal whit the success or failed message, the data of the 3 steps should be saved on the local storage, the submit button should be disabled and just enable when all the field are filled correctly. And when user click in the back button can see the second step.

- Form field details:

 - The first step is personal data with the fields: document(for example cpf), email, name, lastname and birth date .
 - The second step is address data with the fields: city, street, number, complemet, state, district and country. Integrate using address api is a good bonus.
 - The last step is accept of terms data with the fields: email (disabled and typed with the recovered value of input email saved in the first step), and a checkbox to accept of terms.


### Developer Notes

For this exercise the developer should use a javascript framework like angular, reactjs or vuejs.

## Bonus features

-   [ ] Developer can use a lib or module to handler the form like react hook form if use reactjs.
-   [ ] Developer can integrate the form whit firebase realtime database to save the data instead to use local storage.

## Useful links and resources

- [Tutorial Web Dev Simplified](https://www.youtube.com/watch?v=uDCBSnWkuH0)
- [Tutorial Web Decoded](https://www.youtube.com/watch?v=LqRF0MD__gs)

## Example projects

- [Source code Web Dev Simplified](https://github.com/WebDevSimplified/react-multistep-form)
- [Source code Web Decoded](https://github.com/judygab/web-dev-projects/tree/main/react-form)

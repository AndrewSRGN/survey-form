# Survey Form
## freeCodeCamp sertification project
**Objective**: Build an app that is functionally similar to *https://survey-form.freecodecamp.rocks*

User Stories:

1. You should have a page title in an h1 element with an id of title
2. You should have a short explanation in a p element with an id of description
3. You should have a form element with an id of survey-form
4. Inside the form element, you are required to enter your name in an input field that has an id of name and a type of text
5. Inside the form element, you are required to enter your email in an input field that has an id of email
6. If you enter an email that is not formatted correctly, you will see an HTML5 validation error
7. Inside the form, you can enter a number in an input field that has an id of number
8. The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
9. If you enter numbers outside the range of the number input, which are defined by the min and max attributes, you will see an HTML5 validation error
10. For the name, email, and number input fields, you can see corresponding label elements in the form, that describe the purpose of each field with the following ids: id="name-label", id="email-label", and id="number-label"
11. For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field
12. Inside the form element, you should have a select dropdown element with an id of dropdown and at least two options to choose from
13. Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the name attribute
14. Inside the form element, you can select several fields from a series of checkboxes, each of which must have a value attribute
15. Inside the form element, you are presented with a textarea for additional comments
16. Inside the form element, you are presented with a button with id of submit to submit all the inputs

### TESTS
1. ![PASSED](./img/passed.svg) Passed: You should have an h1 element with an id of title.
2. ![PASSED](./img/passed.svg) Passed: Your #title should not be empty.
3. ![PASSED](./img/passed.svg) Passed: You should have a p element with an id of description.
4. ![PASSED](./img/passed.svg) Passed: Your #description should not be empty.
5. ![PASSED](./img/passed.svg) Passed: You should have a form element with an id of survey-form.
6. ![PASSED](./img/passed.svg) Passed: You should have an input element with an id of name.
7. ![PASSED](./img/passed.svg) Passed: Your #name should have a type of text.
8. ![PASSED](./img/passed.svg) Passed: Your #name should require input.
9. ![PASSED](./img/passed.svg) Passed: Your #name should be a descendant of #survey-form.
10. ![PASSED](./img/passed.svg) Passed: You should have an input element with an id of email.
11. ![PASSED](./img/passed.svg) Passed: Your #email should have a type of email.
12. ![PASSED](./img/passed.svg) Passed: Your #email should require input.
13. ![PASSED](./img/passed.svg) Passed: Your #email should be a descendant of #survey-form.
14. ![PASSED](./img/passed.svg) Passed: You should have an input element with an id of number.
15. ![PASSED](./img/passed.svg) Passed: Your #number should be a descendant of #survey-form.
16. ![PASSED](./img/passed.svg) Passed: Your #number should have a type of number.
17. ![PASSED](./img/passed.svg) Passed: Your #number should have a min attribute with a numeric value.
18. ![PASSED](./img/passed.svg) Passed: Your #number should have a max attribute with a numeric value.
19. ![PASSED](./img/passed.svg) Passed: You should have a label element with an id of name-label.
20. ![PASSED](./img/passed.svg) Passed: You should have a label element with an id of email-label.
21. ![PASSED](./img/passed.svg) Passed: You should have a label element with an id of number-label.
22. ![PASSED](./img/passed.svg) Passed: Your #name-label should contain text that describes the input.
23. ![PASSED](./img/passed.svg) Passed: Your #email-label should contain text that describes the input.
24. ![PASSED](./img/passed.svg) Passed: Your #number-label should contain text that describes the input.
25. ![PASSED](./img/passed.svg) Passed: Your #name-label should be a descendant of #survey-form.
26. ![PASSED](./img/passed.svg) Passed: Your #email-label should be a descendant of #survey-form.
27. ![PASSED](./img/passed.svg) Passed: Your #number-label should be a descendant of #survey-form.
28. ![PASSED](./img/passed.svg) Passed: Your #name should have a placeholder attribute and value.
29. ![PASSED](./img/passed.svg) Passed: Your #email should have a placeholder attribute and value.
30. ![PASSED](./img/passed.svg) Passed: Your #number should have a placeholder attribute and value.
31. ![PASSED](./img/passed.svg) Passed: You should have a select field with an id of dropdown.
32. ![PASSED](./img/passed.svg) Passed: Your #dropdown should have at least two selectable (not disabled) option elements.
33. ![PASSED](./img/passed.svg) Passed: Your #dropdown should be a descendant of #survey-form.
34. ![PASSED](./img/passed.svg) Passed: You should have at least two input elements with a type of radio (radio buttons).
35. ![PASSED](./img/passed.svg) Passed: You should have at least two radio buttons that are descendants of #survey-form.
36. ![PASSED](./img/passed.svg) Passed: All your radio buttons should have a value attribute and value.
37. ![PASSED](./img/passed.svg) Passed: All your radio buttons should have a name attribute and value.
38. ![PASSED](./img/passed.svg) Passed: Every radio button group should have at least 2 radio buttons.
39. ![PASSED](./img/passed.svg) Passed: You should have at least two input elements with a type of checkbox (checkboxes) that are descendants of #survey-form.
40. ![PASSED](./img/passed.svg) Passed: All your checkboxes inside #survey-form should have a value attribute and value.
41. ![PASSED](./img/passed.svg) Passed: You should have at least one textarea element that is a descendant of #survey-form.
42. ![PASSED](./img/passed.svg) Passed: You should have an input or button element with an id of submit.
43. ![PASSED](./img/passed.svg) Passed: Your #submit should have a type of submit.
44. ![PASSED](./img/passed.svg) Passed: Your #submit should be a descendant of #survey-form.


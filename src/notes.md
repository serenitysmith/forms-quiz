1. In a vanilla JS app, at what point in the form submission
   process do you gather all the data from the filled-out form?


<!-- Right before the form is submitted -->


2. In a React app, when do you gather all the data from
   the filled-out form?


<!-- while the form is being filled out, all the data isheld in local state -->




3. Which attribute in the form elements (value, name, onChange, etc.) 
   should match the property name being held in state for that input? 
   
   
   <!-- name, helps us in or on change to know which property of state we are acessessing  -->


4. What's different about a saving the data from a checkbox element
   vs. other form elements?
<!-- 
A checkbox uses the `checked` property to determine what should
be saved in state. Other form elements use the `value` property instead. -->


5. How do you watch for a form submit? How can you trigger
   a form submit?
   
   
   <!-- - Can watch for the submit with an onSubmit handler on the `form` element.
- Can trigger the form submit with a button click.
   onSubmit handler on the `form` element. and pass a funnction to the on submit handler that will run every time the form is submitted
   button click trigers form to submit  -->
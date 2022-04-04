Create a new angular project called basic-ngmodel-exercise
In app.component.ts, create a instance property called title of type string and set it equal to "header"
In app.component.html, create an h1 element and use string interpolation to output the value of the instance property header.
Create an input element that implements two-way data binding, ngModel, that will dynamically change the header's value for whenever you type into the input field.
run ng serve to confirm this works.

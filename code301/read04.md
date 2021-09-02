# React and Forms  

HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state .  


This form has the default HTML form behavior of browsing to a new page when the user submits the form. If you want this behavior in React, it just works. But in most cases, it’s convenient to have a JavaScript function that handles the submission of the form and has access to the data that the user entered into the form. The standard way to achieve this is with a technique called “controlled components”.  

## What is a ‘Controlled Component’?

A Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange. A parent component "controls" it by handling the callback and managing its own state and passing the new values as props to the controlled component. You could also call this a "dumb component".  

### The textarea Tag  
In React, a < textarea> uses a value attribute instead. This way, a form using a < textarea> can be written very similarly to a form that uses a single-line input.  

### The select Tag  
In HTML, < select > creates a drop-down list.
React, instead of using this selected attribute, uses a value attribute on the root select tag. This is more convenient in a controlled component because you only need to update it in one place.  

Overall, this makes it so that < input type="text">, < textarea>, and < select> all work very similarly - they all accept a value attribute that you can use to implement a controlled component.  

### The file input Tag  

In HTML, an < input type="file"> lets the user choose one or more files from their device storage to be uploaded to a server or manipulated by JavaScript via the File API.
Because its value is read-only, it is an uncontrolled component in React.  

### Handling Multiple Inputs  
When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.  

### Controlled Input Null Value  
Specifying the value prop on a controlled component prevents the user from changing the input unless you desire so. If you’ve specified a value but the input is still editable, you may have accidentally set value to undefined or null.  

## JavaScript — The Conditional (Ternary) Operator Explained  

**Starting With the Basics — The if statement**  

Using a conditional, like an if statement, allows us to specify that a certain block of code should be executed if a certain condition is met.
Consider the following example:
We have a `person` object that consists of a `name, age`, and `driver` property.  

*`let person = {`*  
  *`name: 'tony',`*  
  *`age: 20,`*  
  *`driver: null`*  
*`};`*  
    

    We want to test if the age of our `person` is greater than or equal to `16`. If this is true, they’re old enough to drive and `driver` should say `'Yes'`. If this is not true, `driver` should be set to `'No'`.  

We could use an if statement to accomplish this:  
  
*`if (person.age >= 16) {`*  
  *`person.driver = 'Yes';`*  
*`} else {`*  
  *`person.driver = 'No';`*  
*`}`*  



  But what if I told you we could do the same exact thing in just one line of code? Well, here it is:  

  *person.driver = person.age >=16 ? 'Yes' : 'No';*  

  This shorter code yields us the same result of `person.driver = 'Yes';`  


Now that you’ve seen the conditional ternary operator in action, we can explore how it works!   

### The Conditional (Ternary) Operator  

First, we’ll take a look at the syntax of a typical if statement:

*`if ( condition ) {`*  
  *`value if true;`*  
*`} else {`*  
  *`value if false;`*  
*`}`*  

Now, the ternary operator:  

*`condition ? value if true : value if false`*  

*Here’s what you need to know:*  

1. The condition is what you’re actually testing. 
 The result of your condition should be true or false or at least coerce to either boolean value.  

2. A ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.  

3. Finally a : colon. If your condition evaluates to false, any code after the colon is executed.  


**Rewrite the following statement using a ternary statement:**  


  *`if(x===y){`*    
 *`console.log(true);`*  
  *`} else {`*  
 *`console.log(false);`*  
  *`}`*  

  The result is :

  *`(x===y) ? console.log(true) : console.log(false)`*



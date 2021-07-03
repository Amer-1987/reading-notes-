# Function in JavaScript

Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

![JavaScript Function](https://miro.medium.com/max/700/1*dAwQkc-E0j1AcpdPeGznzg.png)

## Defining functions  :  

* ### Function declarations  
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:  

1. The name of the function.  
2. A list of parameters to the function, enclosed in parentheses and separated by commas.
3. The JavaScript statements that define the function, enclosed in curly brackets, {...}.


* ### Function expressions :  
While the function declaration above is syntactically a statement, functions can also be created by a function expression.  

Such a function can be anonymous; it does not have to have a name. 



![different](https://i.stack.imgur.com/lcPvN.png)

## Calling functions :  
Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.

Calling the function actually performs the specified actions with the indicated parameters.  

#
  
## Control flow  

The *control flow* is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:
 
if (field==empty) {  
    promptUser();  
} else {  
    submitForm();  
}  

Thanks for huge efforts `our teachers` .
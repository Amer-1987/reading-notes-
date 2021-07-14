# Debugging

`JavaScript` can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.   

![debugging](https://image.slidesharecdn.com/debugging-javascript-web-141030080414-conversion-gate02/95/debugging-javascript-1-638.jpg)

***ORDER OF EXECUTION***  
To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex; some tasks 
cannot complete until another statement or function has been run.

***EXECUTION CONTEXTS  ***  
The JavaScript interpreter uses the concept of execution contexts. 
There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.  


`EXECUTION CONTEXT`  

Every statement in a script lives in one of three execution contexts: 
* GLOBAL CONTEXT   
Code that is in the script, but not in a function. 
There is only one global context in any page. 
FUNCTION CONTEXT Code that is being run within a function. 
Each function has its own function context.   
* EVAL CONTEXT  
Text is executed like code in an internal function called eva 1 ().  

`VARIABLE SCOPE`  

The first two execution contexts correspond with the notion of scope: 
* GLOBAL SCOPE 
If a variable is declared outside a function, it can be used anywhere because it has global scope. 
If you do not use the var keyword when creating a variable, it is placed in global scope.   
* FUNCTION-LEVEL SCOPE 
When a variable is declared within a function, it can only be used within that function. This is because it has function-level scope.  


## EXECUTION CONTEXT & HOISTING 
1: **PREPARE **  
• The new scope is created   
• Variables, functions, and arguments are created   
• The value of the this keyword is determined   

2: **EXECUTE **  
• Now it can assign values to variables   
• Reference functions and run their code   
• Execute statements   

![EXECUTION CONTEXT](https://www.learnsimpli.com/wp-content/uploads/2020/02/4-6.png)  

### UNDERSTANDING SCOPE :
In the interpreter, each execution context has its own variables object.   
It holds the variables, functions, and parameters available within it.   
Each execution context can also access its parent's variables object.  

### UNDERSTANDING ERRORS :  
If a JavaScript statement generates an error, then it throws an exception.   
At that point, the interpreter stops and looks for exception-handling code.   
  

### ERROR OBJECTS :
Error objects can help you find where your mistakes are and browsers have tools to help you read them.  

When an Er ror object is created, it will contain the 
following properties:  

PROPERTY    | DESCRIPTION                |
------------|:------------------------ |
name | Type of execution |
message | Description |
file Number | Name of the JavaScript file |
line Number | Line number of error | 


There are seven types of built-in error objects in JavaScript. You'll see them on the next two pages:   

OBJECT    | DESCRIPTION                |
------------|:------------------------ |
Error | Syntax Error |
Generic error | the other errors are all based upon this error |
Syntax error | has not been followed |
Reference Error | Tried to reference a variable that is not declared/within scope |
TypeError | An unexpected data type that cannot be coerced |
Range Error | Numbers not in acceptable range | 
URI Error |encodeURI ().decodeURI(),and similar methods used incorrectly|
Eval Error | eva l () function used incorrectly|  

### HOW TO DEAL WITH ERRORS :  
Now that you know what an error is and how the browser treats them, there are two things you can do with the errors.   

![handle with errors](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Debugging-and-Testing.png)

1: **DEBUG THE SCRIPT TO FIX ERRORS**   

If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, 
and fix it. You will find that the developer tools available in every major modern browser will help you with this task. In this chapter, you will learn about the developer tools in Chrome and Firefox. (The tools in Chrome are identical to those in Opera.)   

2: **HANDLE ERRORS GRACEFULLY**   

You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements. Sometimes, an error may occur in the script for a reason beyond your control. For example, you might request data from a third party, and their server may not respond. In such cases, it is particularly important to write error-handling code.   


### Highlight :  

* If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.   
* Debugging is the process of finding errors. It involves a 
process of deduction.   
* The console helps narrow down the area in which the error is located, so you can try to find the exact error.   
* JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error.   
* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements.   

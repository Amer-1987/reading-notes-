#  Problem Domain, Objects, and the DOM

## What is an Object?  
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 

If a *variable* is part of an object, it is called a **property**. Properties tell us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms.

If a *function* is part of an object, it is called a **method**. 
Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms.  

Programmers use a lot of name/value pairs:   
• **HTML** uses attribute names and values.   
• **CSS** uses property names and values.   


In **JavaScript**:   
• Variables have a name and you can assign them a value of a string, number, or Boolean.   
• Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.)   
• Named functions have a name and value that is a set of statements to run if the function is called.   
• Objects consist of a set of name/value pairs (but the names are referred to as keys).   

### Creating a JavaScript Object
With JavaScript, you can define and create your own objects.  

![create an object](https://thecodelearners.com/wp-content/uploads/2020/11/Learn-How-to-create-an-Object-in-Javascript-using-Object.create-method-for-Beginners.jpg)

*There are different ways to create new objects:*

1. Create a single object, using an object literal.
2. Create a single object, with the keyword `new`.
3. Define an object constructor, and then create objects of the constructed type.
4. Create an object using `Object.create()`.  

**Using an Object Literal**  
This is the easiest way to create a JavaScript Object.
Using an object literal, you both define and create an object in one statement.
An object literal is a list of name:value pairs (like age:50) inside curly braces {}.

The following example creates a new JavaScript object with four properties:  
*const person = {firstName:"AAmer", lastName:"Alqnahrah", age:34, eyeColor:"blue"};*  

**Using the JavaScript Keyword new**  

The following example create a new JavaScript object using new Object(), and then adds 4 properties:

Example :    
*const person = new Object();  
person.firstName = "Amer";  
person.lastName = "alqnahrah";  
person.age = 34;  
person.eyeColor = "blue";*  

### Highlightes :
* An object is a series of variables and functions that represent something from the world around you. 
* In an object, variables are known as properties of the object; functions are known as methods of the object. 
* Web browsers implement objects that represent both the browser window and the document loaded into the browser window. 
* JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts. 
* Arrays and objects can be used to create complex data sets (and both can contain the other).    

...............................................................................................  


## The HTML DOM (Document Object Model) 

## What is the DOM?
**The DOM** is a W3C (World Wide Web Consortium) standard.

**The DOM** defines a standard for accessing documents:

*The W3C Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document.*  

The W3C DOM standard is separated into 3 different parts:  

* `Core DOM` - standard model for all document types  
* `XML DOM` - standard model for XML documents  
* `HTML DOM` - standard model for HTML documents    

HTML DOM `methods` are **actions** you can perform (on HTML Elements).

HTML DOM `properties` are **values** (of HTML Elements) that you can set or change.  

When a web page is loaded, the browser creates a Document Object Model of the page.

The HTML DOM model is constructed as a tree of Objects:  

![DOM](https://www.w3schools.com/js/pic_htmltree.gif)  

With the object model, JavaScript gets all the power it needs to create dynamic HTML:

* JavaScript can change all the HTML elements in the page
* JavaScript can change all the HTML attributes in the page
* JavaScript can change all the CSS styles in the page
* JavaScript can remove existing HTML elements and attributes
* JavaScript can add new HTML elements and attributes
* JavaScript can react to all existing HTML events in the page
* JavaScript can create new HTML events in the page  



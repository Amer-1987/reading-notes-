# Forms and JS Events  

## Forms  
Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in information.

The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

![google search](https://emadsaber89.files.wordpress.com/2020/05/google.jpeg)  


### Form Controls
**Adding text :**  
* Text input (single-line)   
Used for a single line of text such as email addresses and names.  
* Password input  
Like a single line text box but it masks the characters entered.  
* Text area (multi-line)  
For longer areas of text, such as messages and comments.  


** Maaking Choices :**  
* Submit buttons  
To submit data from your form to another web page.  
* Image buttons  
Similar to submit buttons but they allow you to use an image.   


** Uploading Files :**  
* File upload  
Allows users to upload files (e.g. images) to a website.  

### How Forms Work ?  
1. A user fills in a form and then presses a button to submit the information to the server.  
2. he name of each form control is sent to the server along with the 
value the user enters or selects.  
3. The server processes the information using a programming language 
such as PHP, C#, VB.net, or Java. It may also store the information in a database.  
4. he server creates a new page to send back to the browser based on the information received.  


### Highlight :
* Whenever you want to collect information from visitors you will need a form, which lives inside a <form> element.  
* Information from a form is sent in name/value pairs.
* Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
* HTML5 introduces new form elements which make it easier for visitors to fill in forms.  


## JS Events 
W hen you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.   


* DIFFERENT EVENT TYPES  


EVENT  | DESCRIPTION                                                                                 | 
------------|:--------------------------------------------------- | 
load | Web page has finished loading|
   unload |  Web page is unloading (usually because a new page was requested)  |
   error |   Browser encounters a JavaScript error or an asset doesn't exist  |
  click |  User presses and releases a button over the same element     |
   dbl click   |  User presses and releases a button twice over the same element    |
   moused own  |  User presses a mouse button while over an element    |
  mouseup  | User releases a mouse button while over an element     |
   mousemove  |  User moves the mouse (not on a touchscreen)     |
   mouseover   |   User moves the mouse over an element (not on a touchscreen)   |
   input   |  Value in any <input> or <textarea> element has changed (IE9+) or any element with the contented i table attribute    |
  reset    | User clicks on a form's res~t button (rarely used these days)     |
  submit    |  User submits a form (using a button or a key)     |
  change |  Value in select box, checkbox, or radio button changes (IE9+)   | 
  select  | User selects some text in a form field   |  

### EVENT LISTENERS  
Event listeners are a more recent approach to handling events. 
They can deal with more than one function at a time but they are not supported in older browsers. 

### USING EVENT LISTENERS   

**JAVASCRIPT ex. :**  

*function checkUsername() { *  
 *var e1Msg = document .get ElementByld('feedback'); *  
*if (this.value.lengt h< 5) { *  
*e1Msg.textContent='Username must be 5 characters or more';*  
*} else { *  
*elMsg.textContent='  ';*  
*}*  
*}*  
*var elUsername = document.getElementByld(' username') ;*
*e1Username.addEventlistener('blur' , checkUsername , false);*


**The addEventli stener () method takes three properties:**   
i) The event you want it to listen for. In this case, the b 1 ur event.   

ii) The code that you want it to run when the event fires. 
In this example, it is the checkUsername () function. Note that the parentheses are omitted where the function is called because they would indicate that the function should run as the page loads (rather than when the event fires).   

iii) A Boolean indicating how events flow, see p260. (This is usually set to false.)


  ### Highlight 

* Events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked).   
* Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon. 
* When an event occurs on an element, it can trigger a JavaScript function. When this function then changes the web page in some way, it feels interactive because it has responded to the user. 
* You can use event delegation to monitor for events that happen on all of the children of an element. 
* The most commonly used events are W3C DOM events, although there are others in the HTMLS specification as well as browser-specific events. 
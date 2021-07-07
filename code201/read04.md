# Links

`Links` are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.

![link](https://careerkarma.com/blog/wp-content/uploads/2020/02/html-hyperlink.jpg)

## Linking to Other Sites :

### <a>
Links are created using the <a> element which has an attribute 
called href. The value of the href attribute is the page that 
you want people to go to when they click on the link.  

Users can click on anything that appears between the opening 
<a> tag and the closing </a>tag and will be taken to the page 
specified in the href attribute.  

 When you link to a different website, the value of the href attribute will be the full web address for the site, which is known as an absolute URL.


 ### mailto: 
To create a link that starts up the user's email program and  addresses an email to a specified email address, you use the <a>
element. However, this time the value of the href attribute starts 
with mailto: and is followed by the email address you want the email to be sent to. 

On the right you can see that an email link looks just like any other link but, when it is clicked on, the user's email program will open a new email message and address it to the person specified in the link.


### target :

If you want a link to open in a new window, you can use the target attribute on the opening <a> tag. The value of this attribute should be _blank.  

One of the most common reasons a web page author might want a link to be opened in a new window is if it points to another website. In such cases, they hope the user will return to the window containing their 
site after finishing looking at the other one.  

## Highlights :  

* Links are created using the <a> element.
* The <a> element uses the href attribute to indicate the page you are linking to.
* If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
* You can create links to open email programs with an email address in the "to" field.
* You can use the id attribute to target elements within a page that can be linked to.   


# Layout :

### Building Blocks :  

CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.


* <div> elements are often used as containing elements 
to group together sections of a page.
* Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
* The float property moves content to the left or right of the page and can be used to create multi-column 
layouts. (Floated items require a defined width.)
* Pages can be fixed width or liquid (stretchy) layouts.
* Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
* Grids help create professional and flexible designs.
* CSS Frameworks provide rules for common tasks.
* You can include multiple CSS files in one page.
![layout](https://slidetodoc.com/presentation_image_h/25bf210ce9e0e2a05e0c2c5068267d85/image-9.jpg)

** Absolute Positioning **  
#### Aosition:absolute    

When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) The box offset properties (topor bottom and left or right) specify where the element should appear in relation to its containing element


** Fixed Positioning **  
#### position:fixed

Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls 
down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect.


** Overlapping Elements **  
#### z-index  

When you use relative, fixed, or absolute positioning, boxes can 
overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. For example, an element with a z-index of 10 will appear over the top of one with a z-index of 5.


** Floating Elements  **  
#### float  

The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. Anything else that sits inside the containing element will 
flow around the element that is floated. When you use the float
property, you should also use the width property to indicate how  wide the floated element should be. If you do not, results can be 
inconsistent but the box is likely to take up the full width of the 
containing element (just like it would in normal flow).  


## Screen Sizes

Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.  

## Screen Resolution:

Resolution refers to the number of dots a screen shows per inch. Some 
devices have a higher resolution than desktop computers and most 
operating systems allow users to adjust the resolution of their screens.

.....................................................................


# Functions, Methods, and Objects :

## WHAT IS A FUNCTION?     
![Function](https://miro.medium.com/max/700/1*dAwQkc-E0j1AcpdPeGznzg.png)

*Functions* let you group a series of statements together to perform a 
specific task. If different parts of a script repeat the same task, you can 
reuse the function (rather than repeating the same set of statements). 

JavaScript functions are defined with the function keyword.

You can use a function declaration or a function expression.

### Function Declarations

*Declared functions* are not executed immediately. They are "saved for later use", and will be executed later, when they are invoked (called upon).

Semicolons are used to separate executable JavaScript statements.
Since a function declaration is not an executable statement, it is not common to end it with a semicolon.  


### Function Expressions:  

A JavaScript function can also be defined using an *expression*.
A function expression can be stored in a variable.
After a function expression has been stored in a variable, the variable can be used as a function.
The function above is actually an anonymous function (a function without a name).

Functions stored in variables do not need function names. They are always invoked (called) using the variable name.

The function above ends with a semicolon because it is a part of an executable statement.   

![difference](https://i.stack.imgur.com/bCrSm.png)  




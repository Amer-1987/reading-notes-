# CSS

![Css](https://miro.medium.com/max/600/1*OFsc0SD55jhi8cjo7aCA4w.jpeg)
## What is CSS?  

`CSS` (Cascading Style Sheets) allows you to create great-looking web pages. CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.

## Why use CSS?
`CSS` helps you to keep the informational content of a document separate from the details of how to display it. The details of how to display the document are known as its style. You keep the style separate from the content so that you can:

- Avoid duplication  
- Make maintenance easier  
- Use the same content with different styles for different purposes  

![why css](https://www.thoughtco.com/thmb/-MMd7PngVq3k7lbz_O13DFwWmmY=/2200x1467/filters:fill(auto,1)/change-fonts-using-css-3464229-8dda48c837ea41ccaca06019e639eee2.png)  
#

Your web site might have thousands of pages that look similar. Using `CSS`, you store the style information in common files that all the pages share. When a user displays a web page, the user’s browser loads the style information along with the content of the page. When a user prints a web page, you might provide different style information that makes the printed page easy to read.

In general, you use HTML to describe the content of the document, not its style; you use `CSS` to specify its style, not its content. There are exceptions to this rule, of course, and HTML also provides some ways to specify style. For example, in HTML you can use a <b> tag to make text bold, and you can specify the background colour of a page in its *<body>* tag. When you use `CSS` , you normally avoid using these HTML style features so that all your document’s style information is in one place.
#
## How To Add CSS  

When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.

![css selectors](https://s3.eu-west-2.amazonaws.com/uploads.3alampro.com/old/monthly_2018_01/css-selectors-1f0064.png.d03086c298b6ce0f85c394976d9ccacb.png)
#
### Three Ways to Insert CSS  : 

- **External CSS**  :
An external style sheet can be written in any text editor, and must be saved with a css extension.
The external css file should not contain any HTML tags.  


- **Internal CSS**  :
An internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the <style> element, inside the head section.    


- **Inline CSS** :  An inline style may be used to apply a unique style for a single element. To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.  


### CSS color Property :  
The color property specifies the color of text.    

example                                | code                                         |  
---------------------------------------|:---------------------------------------------|  
Set the text color with a HEX value:   | *body {color: #92a8d1;}*                     |
Set the text color with an RGB value:  | *body {color: rgb(201, 76, 76);}*            |
Set the text color with an RGBA value: | *body {color: rgba(201, 76,76, 0.6);}*       |
Set the text color with a HSL value:   |*body {color: hsl(89, 43%, 51%);}*            | 
Set the text color with a HSLA value:  | *body {color: hsla(89, 43%, 51%, 0.6);}*     |   

to see color, visit this link :  [Css Color](https://www.w3schools.com/cssref/css_colors.asp)  

#
### CSS background-color Property
 The background-color property sets the background color of an element.
The background of an element is the total size of the element, including padding and border (but not the margin).

`Tip`: Use a background color and a text color that makes the text easy to read.   

![css background](https://i.ytimg.com/vi/Vzu6DLWpy9Y/maxresdefault.jpg)

`Example` :  

Set background colors for different elements:   

*body {  
  background-color: #fefbd8;  
}*
#  

*h1 {  
  background-color: #80ced6;  
}* 
#  

*div {  
  background-color: #d5f4e6;  
}*

#  

*span {  
  background-color: #f18973;  
}*  
 
#  


***@Amer Alqnahrah***

*Thanks to all staff that don't save any effort to help us.*   

#
#
#
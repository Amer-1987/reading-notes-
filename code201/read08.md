# Layout  


## Positioning Elements :

Building Blocks :  
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.  

Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.   
![block and inline](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/06/Block-level-Inline-elements-in-html-df.jpg)

**Block-level elements**  
start on a new line
Examples include:  
*<h1> <p> <ul> <li>*    


**Inline elements**  
flow in between 
surrounding text
Examples include:  
*<img> <b> <i>*  
![block vs inline](https://i1.wp.com/www.differencebetween.com/wp-content/uploads/2018/02/Difference-Between-Block-and-Inline-Elements-fig-1.png)


### Controlling the Position of Elements :
* Normal flow  (position:static)  
* Relative Positioning  (position:relative)  
* Absolute positioning  (position:absolute)  
* Fixed Positioning  (position:fixed)  
* Floating Elements  

![Position](https://cdn.educba.com/academy/wp-content/uploads/2019/12/CSS-Position.jpg)

### Overlapping Elements :  
**z-index**  
When you use relative, fixed, or absolute positioning, boxes can 
overlap. If boxes do overlap, the elements that appear later in the 
HTML code sit on top of those that are earlier in the page. 
If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. For example, an element with a z-index of 10 will appear over the top of one with a z-index of 5.  

The z-index is sometimes referred to as the stacking context (as if the blocks have been stacked on top of each other on a z axis). If you are familiar with desktop publishing packages, it is the equivalent of using the 'bring to front' and 'send to back' features.  

### Floating Elements
**float**  
The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.

Anything else that sits inside the containing element will 
flow around the element that is floated.
When you use the float property, you should also use the width property to indicate how wide the floated element should be.

If you do not, results can be inconsistent but the box is likely to take up the full width of the containing element (just like it would in normal flow).  

## Screen Sizes :  
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.  
![screen size](https://www.seobility.net/en/wiki/images/6/6f/Media-Queries.png)

The size of a user's screen affects how big they can open their windows and how much of the page they will see. There are also an increasing number of handheld devices (mobile phones and tablets) that have smaller screens.  

### Screen Resolution :  
Resolution refers to the number of dots a screen shows per inch. Some 
devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.  

### Page Sizes :  
Because screen sizes and display resolutions vary so much, web 
designers often try to create pages of around 960-1000 pixels wide 
(since most users will be to see designs this wide on their screens).  

## Highlights :

* <div> elements are often used as containing elements 
to group together sections of a page.
* Browsers display pages in normal flow unless you 
specify relative, absolute, or fixed positioning.
* The float property moves content to the left or right 
of the page and can be used to create multi-column 
layouts. (Floated items require a defined width.)
* Pages can be fixed width or liquid (stretchy) layouts.
* Designers keep pages within 960-1000 pixels wide, 
and indicate what the site is about within the top 600 
pixels (to demonstrate its relevance without scrolling).
* Grids help create professional and flexible designs.
* CSS Frameworks provide rules for common tasks.
* You can include multiple CSS files in one page.
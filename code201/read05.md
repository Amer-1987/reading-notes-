# HTML Images; CSS Color & Text

##  HTML Images :

There are many reasons why you might 
want to add an `image` to a web page: you 
might want to include a logo, photograph, 
illustration, diagram, or chart.
There are several things to consider when selecting and 
preparing images for your site, but taking time to get them 
right will make it look more attractive and professional.
In this chapter you will learn how to:  

● Include an image in your web pages using HTML  
● Pick which image format to use  
● Show an image at the right size  
● Optimize an image for use on the web to make pages load faster.   

![image beside each other](https://images.saymedia-content.com/.image/t_share/MTc0NjQxMjIzMDY2NDYyMTk4/how-to-align-images-side-by-side.jpg)    
If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.  

* *`<img>`* chapter-05/adding-images.html HTML To add an image into the page you need to use an <img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:  


* *`src`*
This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site.  
  

* *`alt`*   
This provides a text description of the image which describes the image if you cannot see it.
title You can also use the title attribute with the <img> element 
to provide additional information about the image. Most browsers 
will display the content of this attribute in a tootip when the user hovers over the image.  

![add image](https://www.codegrepper.com/codeimages/how-to-add-a-link-to-an-image-in-html.png)

You will also often see an <img> element use two other attributes 
that specify its size:  

* height  
This specifies the height of the image in pixels.  

* width  
This specifies the width of the image in pixels.    


 
 ![height and width of image](https://www.wikihow.com/images/thumb/0/00/Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg/v4-460px-Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg.webp)

### Highlight :  

* The *<img>* element is used to add images to a  web page.
* You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
* You should save images at the size you will be using them on the web page and in the appropriate format.
* Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.    


   ..............................................................................  



## Colors :  
very color on a computer screen is created by mixing amounts of ** red, green, and blue**. To find the color you want, you can use a color picker. Understanding Color Computer monitors are made up of thousands of tiny squares called pixels (if you look very closely at your monitor you should be able to see them).  

![colors](https://res.cloudinary.com/practicaldev/image/fetch/s--DIXBsZGD--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/f5vqq3uckm57x5t9pov8.png)

When the screen is not turned on, it's **black** because it's not emitting any light. When it's on, each pixel can be a different color, creating a picture.  

The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue — just like on a television screen. 

olor picking tools are available in image editing programs like Photoshop and GIMP. You can see the RGB values specified next to the radio buttons that say R, G, B.  

![RGB color](https://tutorial.techaltum.com/images/css-colors.jpg)

**The hex value** is provided next to the pound or hash `# symbol`. There is also a good color picking tool at: colorschemedesigner.com  

CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values 

* **hue** :    
Hue is the colloquial idea of color. In HSL colors, hue is often 
represented as a color circle where the angle represents the color,although it may also be shown as a slider with values 
from 0 to 360.  

* **saturation** :  
Saturation is the amount of gray in a color. Saturation is 
represented as a percentage. 100% is full saturation and 0% 
is a shade of gray.  

* **lightness** :  
Lightness is the amount of white (lightness) or black (darkness) in a color. Lightness is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as luminosity.  

![colors in css](https://blog.hubspot.com/hs-fs/hubfs/Google%20Drive%20Integration/Draft%20-%20CSS%20Colors-4.png?width=600&name=Draft%20-%20CSS%20Colors-4.png)
### Highlight :

* `Color` not only brings your site to life, but also helps convey the mood and evokes reactions.
* There are three ways to specify colors in CSS:
1. *RGB values.*  
2. *hex codes.*  
3. *color names.*
* Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.  

.....................................................................................  

## Text :  


###### 18pt
##### 24pt
#### 36pt
### 48pt
## 60pt
# 72pt  
 

* There are properties to control the choice of font, size, 
weight, style, and spacing.
* There is a limited choice of fonts that you can assume 
most people will have installed.
* If you want to use a wider range of typefaces there are 
several options, but you need to have the right license 
to use them.
* You can control the space between lines of text, 
individual letters, and words. Text can also be aligned 
to the left, right, center, or justified. It can also be 
indented.
* You can use pseudo-classes to change the style of an 
element when a user hovers over or clicks on text, or 
when they have visited a link.  


**Weight** :  
Light  
Medium  
Bold  
Black    

**Style** :  
Normal  
Italic  
Oblique  

**Stretch** :   
Condensed  
Regular  
Extended   

#

***`Full thanks to whole team that teach us`***
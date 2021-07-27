# Images, Audio and Video  

## Images 

### Controlling size of images in CSS  

You can control the size of an image using the width and height properties in CSS, just like you can for any other box.    

Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.   

You might think that your site is likely to have images of all different sizes, but a lot of sites use the same sized image across 
many of their pages.  



###  Aligning images in CSS  

The <img> element's align attribute, web page authors are increasingly using the float property to align images.    

** There are two ways that this is commonly achieved: **   

1: The float property is added to the class that was created to 
represent the size of the image (such as the small class in our 
example).  

2: New classes are created with names such as align-left or align-right to align the images to the left or right of the page. 
These class names are used in addition to classes that indicate the size of the image.  

It is also common to add a margin to the image to ensure that the text and other contents do not touch their edges.  




 ## Audio and Video  

 HTML5 comes with elements for embedding rich media in documents — <video> and <audio> — which in turn come with their own APIs for controlling playback, seeking, etc.  

 ### HTML5 video and audio  

The <video> and <audio> elements allow us to embed video and audio into web pages. 

### Audio : 


The <audio> tag is used to embed sound content in a document, such as music or other audio streams.

The <audio> tag contains one or more <source> tags with different audio sources. The browser will choose the first source it supports.

The text between the <audio> and </audio> tags will only be displayed in browsers that do not support the <audio> element.

There are three supported audio formats in HTML: MP3, WAV, and OGG. 

**Attributes**   

Attribute	| Value |	Description |  
----------| ------| ----------- |
autoplay	|autoplay| Specifies that the audio will start playing as soon as it is ready|
controls|	controls|	Specifies that audio controls should be displayed (such as a play/pause button etc)|
loop|	loop|	Specifies that the audio will start over again, every time it is finished|
muted|	muted|	Specifies that the audio output should be muted|
preload|	auto metadata none |	Specifies if and how the author thinks the audio should be loaded when the page loads|
src|	URL|	Specifies the URL of the audio file|  

### Video :
The <video> tag is used to embed video content in a document, such as a movie clip or other video streams.  


The <video> tag contains one or more <source> tags with different video sources. The browser will choose the first source it supports.  


The text between the <video> and </video> tags will only be displayed in browsers that do not support the <video> element.

There are three supported video formats in HTML: MP4, WebM, and OGG.  


Attribute |	Value |	Description |  
--------- | ------| ------------|
autoplay |	autoplay|	Specifies that the video will start playing as soon as it is ready|
controls|	controls|	Specifies that video controls should be displayed (such as a play/pause button etc).|
height|	pixels|	Sets the height of the video player|
loop |	loop |	Specifies that the video will start over again, every time it is finished |
muted	| muted |	Specifies that the audio output of the video should be muted |
poster |	URL |	Specifies an image to be shown while the video is downloading, or until the user hits the play button |  
preload | auto metadata none|Specifies if and how the author thinks the video should be loaded when the page loads |
src |	URL	| Specifies the URL of the video file |
width|	pixels |	Sets the width of the video player |






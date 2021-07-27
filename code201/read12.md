# Chart.js, Canvas  

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.  

## Chart.js comes with the following built-in chart types:

* Scatter  
* Line  
* Bar  
* Radar  
* Pie and Doughnut  
* Polar Area  
* Bubble  
  

 ## How to Use Chart.js?

* First, add a link to the providing CDN (Content Delivery Network) in html file:  

like this :  * < script >
src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.9.4/Chart.js" > 
</ script > *
 

* Then, add a <canvas> to where you want to draw the chart:    

like this :  * < canvas id="myChart" style="width:100%;max-width:700px" ></ canvas >*

The canvas element must have a unique id.  

** Typical Bar Chart Syntax:  **

*var myChart = new Chart("myChart", {  
  type: "bar",  
  data: {},  
  options: {}  
});*  



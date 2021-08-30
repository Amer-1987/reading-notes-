# Passing Functions as Props

## Definition and Usage
The map() method creates a new array with the results of calling a function for every array element.

The map() method calls the provided function once for each element in an array, in order.

map() does not execute the function for empty elements.

map() does not change the original array. 


### Parameters:  
 This method accepts two parameters as mentioned above and described below:

* function(currentValue, index, arr): It is required parameter and it runs on each element of array. It contains three parameters which are listed below:
* currentValue: It is required parameter and it holds the value of current element.
* index: It is optional parameter and it holds the index of current element.
* arr: It is optional parameter and it holds the array.
* thisValue: It is optional parameter and used to hold the value of passed to the function.  

### Return Value:  
 It returns a new array and elements of arrays are result of callback function.  

 A “key” is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists. The next thing that comes to mind is that what should be good to be chosen as key for the items in lists. 


 ### How to Use the Spread Operator (…) in JavaScript
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments. 


### What else can … do?  
The spread operator is useful for many different routine tasks in JavaScript, including the following:  
* copying an array  
* Concatenating or combining arrays  
* Using Math functions  
* Using an array as arguments  
* Adding an item to a list  
* Adding to state in React  
* Combining objects  
* Converting NodeList to an array  
In each case, the spread syntax expands an iterable object, usually an array, though it can be used on any interable, including a string.
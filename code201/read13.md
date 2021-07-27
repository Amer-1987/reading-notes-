# Local Storage  

Persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.  

![](https://coursework.vschool.io/content/images/2015/10/localstorage.jpg)


## Using Html5 Storage :  

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.  


*interface Storage {  
  getter any getItem(in DOMString key);  
  setter creator void setItem(in DOMString key, in any data);  
};*  


**Calling setItem()** with a named key that already exists will silently overwrite the previous value. Calling `getItem()` with a non-existent key will return null rather than throw an exception.  

Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the `getItem()` and `setItem()` methods, you can simply use square brackets.  

*var foo = localStorage.getItem("bar");  
// ...  
localStorage.setItem("bar", foo);*  


**…could be rewritten to use square bracket syntax instead: ** 

*var foo = localStorage["bar"];  
// ...  
localStorage["bar"] = foo;*  

There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

*interface Storage {  
  deleter void removeItem(in DOMString key);  
  void clear();  
};*  

![](https://miro.medium.com/max/1400/1*bXzZ7ModnCiI2PzCOMaxtQ.png)

**Calling removeItem() with a non-existent key will do nothing.**  


Finally, there is a property to get the total number of values in the storage area, and to iterate through all of the keys by index (to get the name of each key).  


*interface Storage {  
  readonly attribute unsigned long length;  
  getter DOMString key(in unsigned long index);  
};*  

If you call key() with an index that is not between 0–(length-1), the function will return `null`.  





# APIs

## What does REST stand for?

A REST API (also known as RESTful API) is an application programming interface (API or web API) that conforms to the constraints of REST architectural style and allows for interaction with RESTful web services. REST stands for representational state transfer and was created by computer scientist Roy Fielding.

## REST APIs are designed around a ____.

implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.

## What is an identifier of a resource? Give an example.

Resource identification refers to the unambiguous reporting of research resources such as genes, organisms, tools, and reagents (such as antibodies). These resources should be reported within publications with enough information that reviewers and subsequent researchers can identify the exact strain or reagent used. Preferably, authors should provide the full, descriptive name of the resource, its source and a unique identifier.

## What are the most common HTTP verbs?

REST APIs use a uniform interface, which helps to decouple the client and service implementations. For REST APIs built on HTTP, the uniform interface includes using standard HTTP verbs to perform operations on resources. The most common operations are GET, POST, PUT, PATCH, and DELETE.

## What should the URIs be based on?

A URL provides the location of the resource. A URI identifies the resource by name at the specified location or URL. Other URIs provide only a unique name, without a means of locating or retrieving the resource or information about it,

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Another factor is that all web requests impose a load on the web server. The more requests, the bigger the load. Therefore, try to avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request. However, you need to balance this approach against the overhead of fetching data that the client doesn't need. Retrieving large objects can increase the latency of a request and incur additional bandwidth costs. For more information about these performance antipatterns, see Chatty I/O and Extraneous Fetching.

## What status code does a successful GET request return?

A successful GET method typically returns HTTP status code 200 (OK).

## What status code does an unsuccessful GET request return?

If the resource cannot be found, the method should return 404 (Not Found).

## What status code does a successful POST request return?

If the method does some processing but does not create a new resource, the method can return HTTP status code 200 and include the result of the operation in the response body. Alternatively, if there is no result to return, the method can return HTTP status code 204 (No Content) with no response body.

If the client puts invalid data into the request, the server should return HTTP status code 400 (Bad Request). The response body can contain additional information about the error or a link to a URI that provides more details.

## What status code does a successful DELETE request return?

If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content), indicating that the process has been successfully handled, but that the response body contains no further information. If the resource doesn't exist, the web server can return HTTP 404 (Not Found).

## How would you match your name using Regex?

RegExr was created by gskinner.com, and is proudly hosted by Media Temple.

Edit the Expression & Text to see matches. Roll over matches or the expression for details. PCRE & JavaScript flavors of RegEx are supported. Validate your expression with Tests mode.

The side bar includes a Cheatsheet, full Reference, and Help. You can also Save & Share with the Community, and view patterns you create or favorite in My Patterns.
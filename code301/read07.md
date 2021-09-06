# REST

## Who is Roy Fielding?

Roy Thomas Fielding (born 1965) is an American computer scientist, one of the principal authors of the HTTP specification and the originator of the Representational State Transfer (REST) architectural style. He is an authority on computer network architecture and co-founded the Apache HTTP Server project.

## What is the HTTP protocol that Fielding and his friends created?

The Hypertext Transfer Protocol (HTTP) is an application-level protocol for distributed, collaborative, hypermedia information systems. It is a generic, stateless, protocol which can be used for many tasks beyond its use for hypertext, such as name servers and distributed object management systems, through extension of its request methods, error codes and headers [47]. A feature of HTTP is the typing and negotiation of data representation, allowing systems to be built independently of the data being transferred.

HTTP has been in use by the World-Wide Web global information initiative since 1990. This specification defines the protocol referred to as "HTTP/1.1", and is an update to RFC 2068.

## What does a GET do?

**The `GET` Method**
GET is used to request data from a specified resource.

GET is one of the most common HTTP methods.

## What does a POST do?

**The `POST` Method**
POST is used to send data to a server to create/update a resource.

The data sent to the server with POST is stored in the request body of the HTTP request.

POST is one of the most common HTTP methods.

**Some other notes on POST requests:**

* POST requests are never cached  
* POST requests do not remain in the browser history  
* POST requests cannot be bookmarked  
* POST requests have no restrictions on data length.

## What does PUT do?

**The `PUT` Method**
PUT is used to send data to a server to create/update a resource.

The difference between POST and PUT is that PUT requests are idempotent. That is, calling the same PUT request multiple times will always produce the same result. In contrast, calling a POST request repeatedly have side effects of creating the same resource multiple times.

## What does PATCH do?

A `patch` is a set of changes to a computer program or its supporting data designed to update, fix, or improve it.[1] This includes fixing security vulnerabilities[1] and other bugs, with such patches usually being called bugfixes or bug fixes.[2][better source needed] Patches are often written to improve the functionality, usability, or performance of a program.

`Patches` may be installed either under programmed control or by a human programmer using an editing tool or a debugger. They may be applied to program files on a storage device, or in computer memory. Patches may be permanent (until patched again) or temporary.
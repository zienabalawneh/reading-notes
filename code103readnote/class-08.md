# APIs


## What does REST stand for?

+ REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. 

## REST APIs are designed around a ____.
+ REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

## What is an identifer of a resource? Give an example.

+ A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: 
`https://adventure-works.com/orders/1`

## What are the most common HTTP verbs?

+ GET, POST, PUT, PATCH, and DELETE.

## What should the URIs be based on?


+ Adopt a consistent naming convention in URIs. 

## Give an example of a good URI.

+ In general, it helps to use plural nouns for URIs that reference collections. It's a good practice to organize URIs for collections and items into a hierarchy. For example, /customers is the path to the customers collection, and /customers/5 is the path to the customer with ID equal to 5. This approach helps to keep the web API intuitive.

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

+ try to avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request.



## What status code does a successful GET request return?

+ A successful GET method typically returns HTTP status code 200 (OK). 

## What status code does an unsuccessful GET request return?

+ If the resource cannot be found, the method should return 404 (Not Found)

## What status code does a successful POST request return?

+ If a POST method creates a new resource, it returns HTTP status code 201 (Created).

## What status code does a successful DELETE request return?

+ If the delete operation is successful, the web server should respond with HTTP status code 204








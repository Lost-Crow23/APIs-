<h1>API's</h1>

<h3>What are API’s? How are they used and why are they so popular?</h3>

Firstly, "API" stands for "application programming interface" and essentially means that a two-way communication can be done
by the use of two computer programs using set of protocols and definitions. They are used by the initial communication between
a product and a service, in turn implementing it automatically. When new or the existing tools or products are designed, APIs are
very flexible which simplifies design and showcases innovations. They can also count as contracts, which means a party can request a
relevant documentation in a specific way, and party 2 has to respond to the request, in that format. They help IT teams and business collaborate, 
where rapid changes within the app can be made. 

APIs are popular due to the factors such as, innovation, which allow rapid innovation and change is easily done, 
efficiency, that automatically allows for more efficient data distribution and adaptability, which adapts through the data migration and the
flexibility of services. 

<h3>Data Transfer Process Diagram</h3>

![API Data transfer Diagram](https://user-images.githubusercontent.com/126012715/232333720-d906bb13-f4ca-44c1-a180-b0affa4f3c2e.png)

<h3>What is a REST API? What makes an API RESTful?</h3>

REST or RESTful, it stands for "Representational state transfer" and is an API is an interface to exchange information securely over the internet that two computer systems use.
it's fundamentally an architechtural style that means a set of rules in order to create web services. It's a client server communicator, which creates an object of the requested data
by the client and values of objects are thus sent in response to the user -"POST, GET, PUT, DELETE". For the API to be RESTful , it has to follow the principles of the REST API, which are
Client-server decoupling, Uniform interface, statelessness, layered system architecture, that it's cacheable and lastly code on demand.

<h3>What is HTTP? (what does it stand for and what is it used for?)</h3>

HTTP stands for Hypertext Transfer Protocol, and is a method for encoding and migrating the information between client and a web server. It's primary protocol for the transmission is the
relevant information is migrated across the internet.

<h3>HTTP Request Structure Diagram </h3>

![HTTP Request Structure diagram](https://user-images.githubusercontent.com/126012715/232333733-3c19ae60-cad0-4f3a-9570-25b9490ad4c6.png)

An HTTP Request structure is made out of three vital components, headers, request line and message body.
The verbs iterate, GET (retrieve single item OR a list of items), POST (create an item), PUT (update and item), and DELETE (delete and item). These are request methods to indicate a desired action to be performed
for a given task. The URL(universal Resource Locator), means that it's a named host, which is located in the server, which includes information that are needed to access the resource.

A version refers to the version number of the http protocol being used. Each version number tells the server what features the client supports and how to interpret the request. HTTP/1.1 and HTTP/2 is the most used
today. 

The header appears before the message body and contains information about the request, like the type of request and the encoding within the body. They are structured as key-value pairs, where key is a specific 
information and value is of that corresponded information. In short headers, allow clients and servers to exchange information. 

The body is the part of the request message containing any additional data beyond the header, it can be used to send data to the server, such as JSON and XML. The body is also optional, such like a HTTP GET as it does not usually have one 
due to rather retrieving data from the server than sending the data. If it does contain a body, it's normally identified by the "Content-Type" header field, which specifies the MIME (multipurpose internet mail extensions) type of the data being sent. 

<h3>HTTP Response Structure Diagram</h3>

The response structure diagram consists of a status line which includes, the Response Code and the HTTP Version. For example, "HTTP/1.1 200 OK" is a status line indicating the version of HTTP the server is using, and the status code "200" meaning it was successful.

![HTTP Response Structure Diagram](https://user-images.githubusercontent.com/126012715/232333744-1f47d5cd-a861-41dd-ae84-d088e88cf4be.png)

<h3>What are the 5 HTTP verbs and what do they do? GET, POST, PUT, PATCH, DELETE ?</h3>

The HTTP verbs are known as HTTP methods, are indicates the request type that is being made by the client to the server, each verbs follow their own purpose.

GET: This method is used to retrieve a resource from the server,a web page or data.

PUT: Sends data to the server being processed, used for form submissions or file uploads.

DELETE: Delete a resource on the server.

HEAD: Retrieves the headers of a resource without actually retrieving the resource itself, used for checking status of a resource.

OPTIONS: Retrieves information about the communication options available for a resource.

PATCH: Partially updates an existing resource on the server.

<h3>What is statelessness ?</h3>

In HTTP, it refers to  design principle that each request sent by a client to a server contains information for the server to fulfill, without the need for the server to store any state or context about the client's previous requests. 
No session data or client state between requests are within a server. 
It is essentially achieved through the use of cookies, to maintain session data on the client side rather than server side.

<h3>What is caching ?</h3>

It is a technique used to enhance the performance of web applications by temporarily storing frequently accessed data or resources in a cache. A storage location that stores copies of data ore resources that are likely to be accessed again.
When a request is made, the server initially checks the cache to see if the requested resource is already stored there. If it is present in the cache, the server can retrieve it from the cache instead of having to generate it from 
scratch, which can significantly reduce time needed to process the request.



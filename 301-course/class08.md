# APIs

## API Design Best Practices

### What is REST?
-  REST stands for Roy Fielding proposed Representational State Transfer (REST) as an architectural approach to designing web services. 
- REST is an APIs that is designed around resources, which are any kind of object, data, or service that can be accessed by the client. Also, it is a resource who has an identifier, which is a URL that uniquely identifies that resource.
 
>  https://adventure-works.com/orders/1
- Clients interact with a service by exchanging representations of resources. Many web APIs use JSON as the exchange format.
ex) A response body represented in JSON {"orderId":1,"orderValue":99.90,"productId":1,"quantity":1}
- REST APIs use a uniform interface, which helps to decouple the client and service implementations.
### Organize the API design around resources
we need to focus on the business entities that the web API exposes. For example, in an e-commerce system, the primary entities might be customers and orders. Creating an order can be achieved by sending an HTTP POST request that contains the order information. The HTTP response indicates whether the order was placed successfully or not. When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).
### Define API operations in terms of HTTP methods
The HTTP protocol defines a number of methods that assign semantic meaning to a request. The common HTTP methods used by most RESTful web APIs are:
- **GET** retrieves a representation of the resource at the specified URI. The body of the response message contains the details of the requested resource.
- **POST** creates a new resource at the specified URI. The body of the request message provides the details of the new resource. Note that POST can also be used to trigger operations that don't actually create resources.
- **PUT** either creates or replaces the resource at the specified URI. The body of the request message specifies the resource to be created or updated.
- **PATCH** performs a partial update of a resource. The request body specifies the set of changes to apply to the resource.
- **DELETE** removes the resource at the specified URI.

## Things I want to know more about.
I want to know more about how to use API around resources.
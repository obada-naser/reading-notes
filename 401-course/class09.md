#  The HTTP Request Lifecycle

When searching anything in google or in browser we use a specific syntax of url to get us connected with the http server and here I will talk about these steps:

1. Local processing: It is when we add the url and it takes the specific part of the url.
2. Resolving an Ip address: after it took the part of url, it resolve it with the IP address in the DNS server and that is done using DNS resolver.
3. Establish a TCP Connection: when it finds the target ip address it establishes a tcp connection and that is reliable connection to start sending and receiving packets between the client and server.
4. Send an HTTP Request: when the connection is established the host sends an http request to the http server that I need these information from this place.
5.  Tearing Down and Cleaning Up: once the data sending and receiving is done it. the client sends a fin packet to the server and with that the four way handshake is finished. And the browser start processing the data.

# Java HTTP Request example

Here we can present a steps to perform HTTP requests by java using the HttpUrlConnection or a HttpClient API:-

* Create HttpUrlConnection: It allows us to perform a basic HTTP request. 
* Creating a request: creating an HttpUrlConnection instance using the openConnection() method of the url.
* Adding Request Parameters: It means we need to add a parameters to request and add doOutput property to true.
* Setting Request Headers: adding headers to the request can be done using the setRequestProperty() method, or to read getHeaderField() method.

* Configuring Timeouts: used to set the timeout and read it.

* Handling Cookies:we can work  with cookies using either CookieManager or HttpCookie.
*  Handling Redirects: enabling or disabling the automate following redirects by using the setInstanceFollowRedirects() method.

and these steps is a true example of http request.


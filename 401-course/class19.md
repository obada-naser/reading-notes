#  Spring and Sockets


There are different levels for network and when we get to higher level we get closer to the client and becomes more specific for the request. Here we will build an application that sends messages between a browser and server by using WebSocket and to specific we will be using a STOMP that resides on the lower-level of webSocket.
In this article we will build a session between the client and the server by sending name and receiving a greeting response.


## the guide to build it.

1. we can start either from scratch and that is by starting from the scratch or by downloading and unzipping the source repository.
2. Adding the dependencies : we need to add the dependencies to make it work as we wish and also the Initializr only provides the basic functionality.

3. Creating the resource representation class: Now after finishing Initializr and dependencies, we can start creating the message we will send to the server. We will start sending the username message as JSON by creating a class. when the server receives the message will send a greeting message also as JSON object.

4. Creating the Controller to handle the message: Now when the client receive the hello message we need to make a controller to send a greeting message back. We will use in the controller an annotation called @MessageMapping.  now when the message is sent to the server, the client needs to wait or we can use sleep method so it does not waste any time.

5. Configuring spring for STOMP message: Now to be able to work the previous work, we need to make the webSocket work as it is the medium between them. So we will configure WebSocketConfig class.
6. Creating A browser client: to make our application works we need the front-end to work so we need to test  the sending and receiving from the server side. So we need to create an index.html file and import SockJS and app.js. Then
7. Executing the application: At last we will execute the application and run the application from @SpringBootApplication and it will add all the the previous annotations to the application.
8. Finally, we will use  http://localhost:8080  with whatever routes we created.
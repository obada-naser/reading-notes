# GraphQL @connection

## Review


### Serverless architecture
Every company or hospital or any organization should have a system to be able to organize it's employee. One part of the system is such an important component and that is the server because it can to store the information.

 The server is a computer device who can store many data but however it has many problems like when the size of the company gets bigger or some of the data maybe lost so its fixing cost increases and the server itself is costly. Therefore many companies introduced the serverless solution and it is the ability to have a server but not in local but cloudily and you can use it by paying not high rent also you can have unlimited size.

 #### Cloud providers
 When we say about the most famous in serverless field or clouding providers we have these companies:

 * IBM openwhisk
 * AWS Lambda
 * Azure Functions
 * Alibaba Function Compute

 And many other companies that can provide this service. Here

 #### serverless VS server   

 1. Pricing :serverless reduces cost unlike traditional server.
 2. Networking: the serverless needs a gateway to get to it so an IP address.
3. Environments: servers needs to a have a specific setting unlike serverless.
4. Timeout: for the serverless there is timeout limit.
5. Scale: serverless provide more scaling for less cost.


### AWS amplify

One of the companies who in serverless is aws. AWS amplify provides a tools that can help the developers to build their own we application without supporting many languages like react and java. The tools that is provided like hosting web applications and manage users and the content of app and many other tools like Authentication, DataStore,Storage etc .. .


## GraphQL

In the previous lab we created a graphQL and tested it the api using the AWS AppSync. Now here we will make the relations between types using the @connection annotation and then using and specify the relation if it was one to one, one to many , or many to many.

### @connection

As any sql database we can create a relationship between the entities and here we have the same concept however the entities are called models and annotated by @model. and @connection as we said we will use it to specify the property that will be connected.

### one to one 
one to one relation means we need to make connection between one to one model like team and project. Here we will define in the schema the id and with one one of them we will define the other model and add @connection annotation and for optional reasons we can define the fields to get connected to other model.

### many to one 
Here because one has a relation with many we need to specify other things in the connection annotation such as the keyName and fields inside the one who is one to many like post for many comments and inside the comments we should have the name who should be the same as keyName and fields that should have the defined ID of the post.

### many to many
Inside the many to many we can have many students in a course and many courses with students. So here we need to add a third model and inside it we can have the query and the key name and fields for each of them.

The limit of the of the objects that can be created from an defined objects is 100. And we can set the limit however we need.



# Related Resources and Integration Testing

## Working with Relationships in Spring Data REST

As we know the models will be added using the spring wireframe using an annotation called entity. This annotation points that the model will be added to the database. Here I will talk about the relationship between entities in spring database.


### One-to-one relationship
we can make an association between two entities and using one-to-one annotation and use them in our database. The repositories and resources should be altered to make it work.

### One-to-Many Relationship 

We can make relationship between one entity to many or the opposite. It can be defined using @oneToMany or @@manytoall. Also to specify the association resource we can use @RestResource. 

### Many-to-Many Relationship

The last relationship between the entities are many to many relationship and it is defined using @ManyToMany.

### Testing the Endpoints
We can test the endpoints using the TestRestTemplate. like any method.

## Integration Testing in Spring

we always used the testing in our work to make sure that our work is working exactly as needed. However, the testing in spring is a  little bit different. Integrated test takes an important role in application development.

Here we will show some steps on how to do the test. 

* Preparation: first we need to add the dependencies.

* Spring MVC Test Configuration:to configure and run spring enabled test : first we need to enable spring in Tests with JUnit5 and that done by using the @ExtendWith annotation then we will use WebApplicationContext to load the applican beans and controllers. then we will mock the web context beans.lastly we will verify the tests configuration.

* Integration tests with it we can verify different things such as the name,response body, send request body with path variable or with query parameters.
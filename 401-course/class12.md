# Spring RESTful Routing & Static Files

## Spring RequestMapping

It used to map web requests and spring controller methods.

There are multiple methods to do a mapping between http requests and a method:

1.  RequestMapping by Path.
2. RequestMapping by HTTP Method.
3. RequestMapping using headers attribute.
4. RequestMapping that is produced by controller.
5. RequestMapping using path variables and there is three types of path variables single, multiple, and regex.
6. RequestMapping using request parameters.
7. Other types of requestMapping such as:
      * multiple paths with the same controller.
      * using multiple request methods with the same controller.
      * using fallback method to make all requests.
### Different annotations to implement Request maps.

* @GetMapping
* @PostMapping
* @PutMapping
* @DeleteMapping
* @PatchMapping 


## Accessing Data with JPA
Here we will discuss how to build an application using the spring data jpa. The application example will store plain java objects in a memory-based database:

### starts with the initializer
We either skip this if we want to skip the basics or do it if we want to start from zero.
So here we initialize the spring.

### Defining an entity.
here we will store an objects that is annotated as jpa entity.

### Creating simple queries.

here we will build simple queries using JPA to store data.

### Creating the application
from the main spring initializer will create a simple application

### Running the application
we need to build an executable jar or from the command line either with gradle or maven using this command ./gradlew build.


## Baeldung: Comparing repositories

There are different types of data types repositories interfaces we can use that will extends the generic repository interface.
And here we will talk about them.

Starting from JpaRepository which extends PagingAndSortingRepository and then the CrudRepository that the PagingAndSortingRepository extends it .

###  CrudRepository
This one provides the typical crud functionality like:
save(),findOne(),findAll(),count(),delete(),exists().

### PagingAndSortingRepository
this one provides methods like findAll(Pageable pageable) that is used to build an implementing the pagination.the properties we provide is: page size, current page number, and sorting.

###  JpaRepository
This one provides jpa that is related to JPA methods like flushing,save and flush, delete and patch.. .Also, it extends the PagingAndSortingRepository so takes its methods also.



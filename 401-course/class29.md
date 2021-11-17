# Room


If not needed  huge size of data to keep it so when we get back to the app any time and even if it was offline from the network then we can use the Room to cache it in our cache and then we need not to get back to the SQLite. Also it is faster to get the mostly used data than when we need to get the data from SQLite.

There are three main components classes for the Room:

1. database class
2. Data entities
3. Data access objects

for each of them has a specific usage like the database class used as an access point to the data, the data entities is like the sql database tables, and DAO's is used for it's methods and they are the most used methods like querying,deleting,updating, and adding.


## Data as entities in Room 
As in the spring boot manipulating database we can define tables for the data and by making each entities as a row and by using the @annotation over the entity to point it as a row of the table and by default the Room will make the name of the class as row in the database. Also, we can use other annotations as such as:
* @PrimaryKey: to uniquely identify the row.
* @Ignore:to ignore some fields.
* @Index :we can use it to specify more than one of fields as a unique.

and many other annotations

## Relationships in Room

Also because we know SQLite database is a relational database so we need to make a relationship between the entities . so the relations here have two methods one called Intermediate data class and here we need to make a class and add an instances of the entities in it but the problem here is that increases the complexity like by creating more classes and with coding will increase the complexity of many classes that we will be using however if we used multimap return type it will decrease the number of classes but will increase number of the queries.
Also, here we have types of relations as before:

1. one-to-one relationships
2. one-to-many relationships
3. many-to-many relationships
4. nested relationships


## Using DAO's in Room

If we need to interact with the data that stored in the cache we need to use DAO methods inside it. Interacting such as deleting,or writing or even updating. so we need to use annotation @DAO above the class and then we will have two approaches either by using the query methods that allows us to write sql methods or by using update,delete,insert methods to change it and each of them uses an annotation.





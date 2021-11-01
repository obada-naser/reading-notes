# Web App Security

there are many relations between the entities like one-to-one, many-to-one, and many to many and here we will talk about many to many relationship and what annotation many-to-many is for.

## Hibernate Many to Many tutorial


### a visual of the relation
many to many relation can specified like when we have many projects and many employees and we can give more than one employee a more than one projects so it is not for each employee a project or the opposite therefore here we will use the employee id as the primary key and project_id as the primary key for the project and we can join them by the join table to connect between them.

### Database 
As for the entities to make the many-to-many to work fine we need a three tables or entities. One for the employee, one for the project, and finally one for the joining table.

### The Model Classes

So to create the tables we need an entities and that is why we create an entity for each table and we join them using @ManyToMany, @JoinTable and @JoinColumn annotations. As for the @ManyToMany annotation is used in both sides but the other annotations we use them in the owning side and for the previous example the employee is the owner so we add them to the employee side. @JoinColumn to specify the linking between them. 

### Execution 
At last, if we need to show the relation we need to execute them and the best way is by using the JUNit tests.

## Security: a humorous overview

From my reading to the article, we can conclude that because of the increasing advance of the technology the privacy became something is most important and we can not escape any steal of our information either by the companies as legal companies or by the hackers or viruses. As for the companies like facebook there is no escape form their stealing however the danger comes from the hackers. The hackers have always search for a methods to get to any unwanted information using different approaches like sending suspicious emails and links or from the address. In the end, our world became less privacy from before even if you are not using the internet they can search any way to get your information. 
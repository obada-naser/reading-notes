# Spring

## Spring App Basics

to build a basic web page we need different things such as the HTTP get request with the parameter if we want to change a thing in the web page.
```
http://localhost:8080/greeting => http://localhost:8080/greeting?name=User

```
### The guide to build a basic spring app

There are two ways to build a basic spring app:

1. starting from scratch.
2. or skipping the basics.

#### skipping the basics
it starts with downloading and zipping the source repository, Then directing into <gs-serving-web-content/initial>, and finally jump to the web controller.

#### starting from scratch
* starting with spring initializer: manually or by downloading the pre-initialized project.

* Create a Web Controller : it is used to control the http web requests and usually represented by the controller in the import. 

* Spring Boot Devtools: as we usually need to see change of our coding in the application , we need to restart and then refresh the page but using the spring boot devtools can speed up the operation.

* Running the Application.

* Test the Application: at last we can use the url to test the application.

* Add a Home Page: and when we finish running and testing the application we can add a home page like in css and html.

## Spring MVC and Thymeleaf

controller classes in the MVC application allow us to prepare a model map that will allow complete abstraction of the view technology. that means it will transform into thymleaf.

And here methods to access data from templates:

1. Spring model attributes.
2. Request parameters.
3. Session attributes.
3. ServletContext attributes.
4. Spring beans.







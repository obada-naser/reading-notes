# Spring Boot and OAuth2

Here we will talk about building an app that can provide login using oAuth and spring boot.

There are five ways used to build the samples and starts from the simple,click,logout, logout,two-providers, to custom-error and it is the most advanced sample. we can run the app using either SocialApplication or using the mvn spring-boot:run.

## Single Sign On With GitHub
 We can create an app with taking advantages from gitHub authentication.

 1. Creating new project: it can be done by creating an empty project.
 
 2. Adding home page: by creating an HTML file css file inside the static.
 3. secure the app with github and spring security:we can add for security an oAth 2.0.
 4. Adding a new GitHub app: using the GitHub’s OAuth 2.0 authentication.
 5. Configuring application.yml.
 6. at last booting up the application.

 These steps meant to get an access token from GetHub to the user so the user when tries to perform anything needs make sure he is permitted.

 ## Adding welcome page
 by adding an explicit link to login , allows the user to choose either to be authenticated or not. and that is done using the conditional statement. 
 
 ### Home Page Public
  to make sure it does not redirect us automatically before showing the page we need to use WebSecurityConfigurerAdapter. and we can make sure it is public with these endpoints also: /, /error, /webjars/** .


  ## Adding logout button 
  To make the user to log out from the app we can use a logout button and it will allow the user to logout.

  * Client side changes: we only need a logout button in this side.

  * Adding a Logout Endpoint: in the server side we need to add and endpoint by extending the configure() method.

  ## Login with GitHub

  by logging in any web app there are a multiple ways showing like logging using GitHub or google.


  ## adding an error page for not authenticated users
  we can provide a specific organization to able to use the assets and if not from this organization it will take him/her to error page.
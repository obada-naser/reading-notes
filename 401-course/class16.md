# Spring Authentication

## Spring Security Architecture

We can use spring security to provide our application with security however it provides a minimum security but if we need more security we need to search more in the spring boots. to do so here we will discuss how security works in spring by using the annotations.

### Authentication and Access Control

There are a definition that is known for security as a basis in any security application and that is called AAA and it stands for "Authentication, Authorization, and Accountability". 

* Authentication: It is like making sure who is using the application.
In the spring authentication uses an an interface called AuthenticationManager which has only one method. And most used implementation is ProviderManager. Also, we can customize the authenticationManger using some helpers like AuthenticationManagerBuilder.

* Authorization or Access Control: when we finish the Authentication we can then start using authorization and it means like limiting the access for the users and the core strategy is AccessDecisionManager.

### Web security

the most important thing in using web or building a web is the security so spring provides us with a web tier security and it is based on servlet or filters. And also we can create and customize the filter chains.

![filters](https://github.com/spring-guides/top-spring-security-architecture/raw/main/images/filters.png)

### Method Security

Also spring provides not only web security and java method executions security and it is used using the ConfigAttribute  Strings.

### Working with Threads
If we want to make the spring security works with a wider and different downstream consumers it should work as a fundamentally thread-bound and that is why it can provide a an access and authentication to many consumers. And it can provides an asynch secure methods usinf the helpers like wrappers and callable.

## Spring Auth Cheat Sheet
we can use this cheat sheet to make a security.
1. setting up user moder.
2. creating a controller.
3. implementing UserDetailsService.
4. implementing UserDetails using ApplicationUser.
5. extending WebSecurityConfigurerAdapter from WebSecurityConfig .
6. Registration page.
7. Login page.




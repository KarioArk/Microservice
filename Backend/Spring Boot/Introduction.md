# Introducing Spring Boot
 
For example, a food ordering application which supports in ordering online have to use a frontend UI, backend (server-side programming), and a database to persist data.

To make the development easy and effective several frameworks were introduced such as Struts, Spring and ORM tools such as Hibernate, Toplink, etc. for the database operations.

Spring is widely used for creating scalable applications. For web applications Spring provides Spring MVC which is a widely used module of spring which is used to create scalable web applications.

But main disadvantage of spring projects is that configuration is really time-consuming and can be a bit overwhelming for the new developers. Making the application production-ready takes some time if you are new to the spring.

The Spring team decided they wanted to provide developers with some utilities which relatively automate the configuration procedures and speeds up the process of building and deploying Spring applications, so they invented Spring Boot.

Spring Boot is a utility project which aims to make it easy to build Spring-based, production-ready applications and services with minimum fuss. 

It provides the shortest way to get a Spring web application up and running with the smallest line of code/configuration out-of-the-box.

Spring has evolved a lot in recent years with many new modules such as spring-boot, spring-security, spring-cloud, etc. 

Another benefit that comes when using Spring Boot is it reduces the development time significantly and provides an overall easier way of getting started with the application.

#### Advantages
Very easy to deploy
Easy to pick up
Saves time
Not much configuration needed
Provides dependency management
Provides annotation-based spring application

#### Disadvantages
Spring boot may unnecessarily increase the deployment binary size with unused dependencies.
If you are a control freak, I doubt Spring Boot would fit your needs.
Spring Boot sticks good with micro services. The Spring Boot artifact's can be deployed directly into Docker containers. In a large and monolithic based applications, I would not encourage you to use Spring Boot.

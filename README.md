## Spring Boot WebClient 

Project serves as a reactive client for consuming RESTful web services w/ Spring WebClient.

Consumes controller from [spring6-reactive-mongo](https://github.com/laurakciic/spring6-reactive-mongo) project.

## Technologies
- Spring WebClient, Spring WebFlux, OAuth, JUnit, Mockito

## Note
- project must run in conjunction with [spring6-auth-server](https://github.com/laurakciic/spring6-auth-server) and [spring6-reactive-mongo](https://github.com/laurakciic/spring6-reactive-mongo) projects

Uses [spring6-auth-server](https://github.com/laurakciic/spring6-auth-server) to obtain the JWT token and utilizes it to work with the resource server to export resources from [spring6-reactive-mongo](https://github.com/laurakciic/spring6-reactive-mongo) using this WebClient project.

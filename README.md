# Sample Spring Boot Application

![GitHub contributors](https://img.shields.io/github/contributors/vasanthpandian/spring-boot-demo.svg) ![GitHub last commit](https://img.shields.io/github/last-commit/vasanthpandian/spring-boot-demo.svg)

It is a sample microservice developed using springboot framework and it exposes REST APIs to perform simple user management operations like creating/deleting/updating/fetching users.

## Getting Started
You can close this repo using the below commands
```
git clone https://github.com/vasanthpandian/spring-boot-app.git
```
In STS, click File -> Import -> Existing Projects into Workspace. In the "Select root directory" field, click "Browse" and navigate to the root directory of your Sagan repository clone and click "Open"

## Available REST APIs
- /api/user/show-all - GET
- /api/user/show/{user-id} - GET
- /api/user/update/{user-id} - PUT
- /api/user/delete/{user-id} - DELETE
- /api/user/create - POST

[Postman Collection](/user-service.postman_collection.json) can be used to test the APIs using Postman

## TODOs
- [x] Eureka
- [ ] Config Server
- [ ] Swagger
- [ ] Zipkin
- [ ] Hystrix
- [ ] Zuul
- [ ] Basic Auth
- [ ] OAuth



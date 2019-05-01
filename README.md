# Sample Spring Boot Application

![GitHub contributors](https://img.shields.io/github/contributors/vasanthpandian/spring-boot-demo.svg) ![GitHub last commit](https://img.shields.io/github/last-commit/vasanthpandian/spring-boot-demo.svg)
[![HitCount](http://hits.dwyl.io/Naereen/badges.svg)](http://hits.dwyl.io/Naereen/badges)

It is a sample microservice developed using springboot which exposes REST APIs to perform below operations.
- Create User
- Update User
- Show User
- Delete User
- Show all Users
- Delete all Users

## REST APIs
- /api/user/show-all - GET
- /api/user/show/{user-id} - GET
- /api/user/update/{user-id} - PUT
- /api/user/delete/{user-id} - DELETE
- /api/user/create - POST

[Postman Collection](/user-service.postman_collection.json) can be used to test the APIs using Postman

## TODOs
- Eureka
- Config Server
- Swagger
- Zipkin
- Hystrix
- Zuul
- Basic Auth
- OAuth



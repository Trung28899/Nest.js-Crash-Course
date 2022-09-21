$ npm i -g @nestjs/cli

Nest.js is a node.js framework, build up on Express.js
Embraces TypeScript & Dependency Injection & Modularity

Angular for backend

Can be used to build MVC apps or REST or GraphQL APIs

Enforces clean code and a clear project structure by giving you a series of building blocks

Make building complex applications easy

https://docs.nestjs.com/

$ npm i -g @nestjs/cli
$ nest new project-name
$ npm run start

main.ts > entry file

Module: combine Provider and Controller
module.ts files

Provider > async task, get data from database
service.ts files

Controller > business logics
controller.ts files

@Controller() setup routes
@Controller(“/user”) > send request to /user

Decorators:
@Get()
@Put()
@Delete()
@Patch()

Method decorator also setup routes
For example:

@Controller(“/user”)
@Get(“123”)

Endpoint is: /user/123

In controller, an AppService is imported and used to handle business logics

This AppService is available because in the app.module.ts file, we specify the AppService in the providers (from app.service.ts) and it’s available

Video: https://www.youtube.com/watch?v=F_oOtaxb0L8&ab_channel=Academind

Continue at 40:09

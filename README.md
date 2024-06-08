Spring boot-React Social Media App
Full-Stack Social App with Spring boot and React

Contents
Tech Stack
Usage
Screenshots
Tech Stack
Client: React, Chakra UI

Server: Java, Spring boot, PostgreSQL

Usage
After running the Web API, you can make HTTP requests like:

https://localhost:8080/api/`CONTROLLER_NAME`/`METHOD_NAME`
CONTROLLER_NAME => Each .java file located in the controllers folder (For example CONTROLLER_NAME for PostsController: Posts )

METHOD_NAME => All of the methods in each .java file in the controllers folder

Sample HTTP GET requests:
List all Posts:
https://localhost:8080/api/posts/getall
List Comments by Post:
https://localhost:8080/api/comments/getallbypost/{postId}
User Register
https://localhost:8080/api/auth/register

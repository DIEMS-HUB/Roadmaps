
## Kubernetes

* Before Starting Kubernetes also known as k8s we should know what is Microservice and Monolithic Architecture <a href="https://www.atlassian.com/microservices/microservices-architecture/microservices-vs-monolith#:~:text=A%20monolithic%20application%20is%20built,of%20smaller%2C%20independently%20deployable%20services.">here</a>

<h3>Microservice vs Monolithic</h3>

- The basic purpose of Microservice architecture is to break the monolithic architecture into separate service
- Lets consider you have an Application with below components 

1. Frontend (User profile, Login, SignUp, etc)
2. Backend  (Authentication)
3. Database (Data)

- Monolithic Architecture (Everything tightly coupled)

![img 1](https://user-images.githubusercontent.com/72307121/210928135-8bedd984-2132-4f01-a2b5-fa3b7709c7e9.png)


- Microservice Architecture (Everything is lossely coupled)

![img 2](https://user-images.githubusercontent.com/72307121/210928175-cb463680-a84c-4593-b46a-6d10e790995b.png)


* Benefits of using an microservice architecture is we can update one component without disturbing other components 
* Example : I want to update the UI of my User profile. So I will only work with User profile not with other components. 

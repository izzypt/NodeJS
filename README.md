# NodeJS

### What is NodeJS ?

- Is a platform built on google Chrome JavaScript Engine for building fast and scalable network applications.
- You can use it to run JavaScript from outside the browser, like the backend of a website.

### NodeJS features

- Asynchronous and event-driven
- Very fast - being built on Chrome V8 engine.
- Single Threaded
- Highly Scalable
- Used to bnuild web servers
- Perfect for building real time applpications
- Helpful for manipulating files on File System.

### On what type of apps should we use NodeJS?
- I/O bound apps
- Data Streaming apps
- Real-time apps
- JSON Api's based apps
- Single Page apps

### Where not to use it?

  It is not advisable to use Node for CPU intensive applications because of the single threaded nature of Node.
  
### You are going to create an API with Node, but ... what is it ?

  An API is an application programming interface, that allows two applications to talk to each other.
  
  Each time , you check the weather on your phone, for example, you're using an API to fetch that information.
  
### What about a Restful API , is that any different ?

  REST stands for Representational State Transfer.
  
  RESTful API's were designed to take advantage of existing protocols, like HTTP protocol.
  
  To build a RESTful API there are some rules we should follow, like :
  
  - Client and Server should be separate from each other and allowed to evolve individually.
  
  - Stateless. Rest API's should be stateless, meaning that, each request to a REST API, can be made indenpendently from one another and each request contains the data to complete itself.
  
  - Use HTTP methods. REST API should use proper http methods, like :
     - GET
     - PUT
     - POST
     - DELETE
     
     Example for your URL design:

![image](https://user-images.githubusercontent.com/73948790/214070434-c13e765b-9f2e-448c-a718-2107d4333033.png)
  
  - The API should send data back in JSON.
  

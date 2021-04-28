# Real time messaging with websockets

#### The WebSocket protocol is one of the ways to make your application handle real-time messages.

#### It is important to know that HTTP is used only for the initial handshake. After it happens, the HTTP connection is upgraded to a newly opened TCP/IP connection that is used by a WebSocke.

#### he WebSocket specification allows using of sub-protocols that operate on a higher, application level. One of them, supported by the Spring Framework, is STOMP.

#### To build the WebSocket server-side, we will utilize the Spring Boot framework which significantly speeds up the development of standalone and web applications in Java. Spring Boot includes the spring-WebSocket module

#### Implementing the WebSocket server-side with Spring Boot:

1. ##### First, we need to add the WebSocket library dependency.
2. ##### Then, we can configure Spring to enable WebSocket and STOMP messaging.
3. ##### Implement a controller that will handle user requests. It will broadcast received message to all users subscribed to a given topic
4. #####

#### Implementing the WebSocket Client

1. ##### Autowire Spring STOMP client.
2. ##### Open a connection.

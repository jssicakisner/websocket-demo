### Chat Application with WebSocket

# Description

This repository is a use case for WebSocket API with Spring Boot to build a simple group chat application. The users can join and leave the chat room, get notifications about new users joining, send public and private messages. The user also have unique usernames.
It is meant as an example to learn how to build and run a WebSocket based microservice.
The methods use Spring frameworks Simple Text Oriented Messaging Protocol (STOMP) implementation for data exchange.

### Technologies used

* Java
* Spring Boot
* WebSocket
* [Using WebSocket to build an interactive web application](https://spring.io/guides/gs/messaging-stomp-websocket/)

### Build and run the app using maven

You can run the app directly without packaging it running the following command inside the project directory.

```bash
mvn spring-boot:run
```

### Contributions

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
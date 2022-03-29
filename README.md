## Chat-Example

This is the source code for a very simple chat example used for the Getting Started guide of the Socket.IO website.

https://socket.io/get-started/chat



![image](https://user-images.githubusercontent.com/80922036/160617062-c08e4f6a-74ce-4263-ba6d-6427bff62b12.png)



## About the Web Sockets 

Writing a chat application with popular web applications stacks like LAMP (PHP) has normally been very hard. It involves polling the server for changes, keeping track of timestamps, and it’s a lot slower than it should be.

Sockets have traditionally been the solution around which most real-time chat systems are architected, providing a bi-directional communication channel between a client and a server.

This means that the server can push messages to clients. Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients.


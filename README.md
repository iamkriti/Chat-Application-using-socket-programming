# Chat-Application-using-socket-programming
This project demonstrates a basic chat application using socket programming in C. The application is split into two parts: a server and a client. The server can handle one client at a time and facilitates basic messaging between the client and server.

# Features
Simple Client-Server Communication: The client sends a message to the server, and the server responds back.<br/>
TCP/IP Socket: Uses TCP/IP protocol for reliable communication.<br/>

# How to Run
Compile the Server and Client Code:

gcc server.c -o server
gcc client.c -o client
Run the Server:

bash
./server

Run the Client in a Different Terminal:

bash

./client

# Communication:

The client sends a predefined message to the server.
The server reads the message and sends a response back.

# Requirements
GCC Compiler
Basic knowledge of terminal/command prompt usage
Understanding of C programming and socket API

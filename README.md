# -Simple-Chat-with-TCP

Introduction
Developed by Thiru Venkat Taral, this project implements a simple chat application using TCP/IP networking protocols with Python. It focuses on demonstrating real-time communication between a server and multiple clients, emphasizing the principles of socket programming and multithreading.

Project Description
The project consists of two main components:

TCP Chat Server: Manages client connections and broadcasts messages to all clients, handling concurrent interactions efficiently.
TCP Chat Client: Allows users to connect to the server, send messages, and receive real-time updates from other chat participants.
The goal is to provide insight into network data transmission, the management of client connections by servers, and the facilitation of real-time communication in a networked environment.

Features
Multi-client support with real-time message broadcasting.
Server-side connection and communication management.
Client-side interface for interactive communication.
Detailed implementation of TCP/IP networking protocols.
Application of multithreading and socket programming in Python.
Installation
Clone the repository to your local machine.
Ensure Python is installed and configured properly.
Navigate to the project directory in your terminal.
Usage
Start the server by running python server.py.
Open another terminal window and run python client.py to start a client.
Repeat step 2 for additional clients as needed.
Technical Details
The server and client scripts (server.py and client.py) are written in Python, utilizing threading for handling multiple client connections and sockets for network communication.
The server listens for incoming connections on a predefined port, managing each client in a separate thread.
Clients connect to the server using its IP address and port, engaging in the chat by sending and receiving messages.
Conclusion
This TCP chat application demonstrates the practical application of network programming concepts in Python, offering a functional and interactive platform for understanding real-time communication over TCP/IP networks.

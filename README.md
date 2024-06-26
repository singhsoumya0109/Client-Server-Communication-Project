# Client-Server-Communication-Project
This repository contains a simple TCP/IP client-server application in Python. The server listens for connections, processes data with a 10-second delay, and returns modified responses. The client connects, sends messages, and displays processed responses with timestamps. The server uses threading to handle multiple clients simultaneously.


## Features

### Server:
- Manages multiple clients concurrently using threading.
- Introduces a 10-second delay before responding to each client request.
- Modifies the echoed data by appending ' (processed)'.

### Client:
- Sends messages to the server and displays the send time.
- Receives messages from the server and shows the receive time.
- Calculates and shows the interval between sending and receiving data.
- Allows the user to send multiple messages until they choose to stop.

## Prerequisites
- Python 3.x

## Getting Started

### Setting up the Server
1. Clone the repository:
   ```bash
   git clone https://github.com/singhsoumya0109/Client-Server-Communication-Project.git
   cd Client-Server-Communication-Project
2. Run the server:
   ```bash
   python server.py

### Setting up the Client
1. Run the server:
   ```bash
   python client.py

### Interaction:
- The client will prompt for a message to send to the server.
- After sending the message, it will display the time of sending.
- The server will process the request with a 10-second delay and send back a modified response.
- The client will display the received message, the time of receiving, and the time interval between sending and receiving.





# Windows Based Chat App in JAVA

This repository contains the source code for a simple chat application implemented in Java, designed to run on Windows.

## Overview

The chat application consists of two components: a client and a server. Users can exchange messages in a chat-like interface. The application uses Java's Socket programming to establish communication between the client and server.

## How to Use

### Running the Server

1. Open the `Server` class.
2. Run the `main` method.
3. The server will be ready to accept connections.

### Running the Client

1. Open the `Client` class.
2. Run the `main` method.
3. The client will attempt to connect to the server.

## Features

- Basic client-server chat application.
- GUI with message input and display areas.
- Multithreaded design for concurrent reading and writing.
- Simple key events for sending messages.

## Code Structure

### Client Class

The `Client` class represents the client-side implementation.

- `Socket` initialization for communication.
- GUI components for the chat interface.
- Reading and writing threads for concurrent communication.

### Server Class

The `Server` class represents the server-side implementation.

- `ServerSocket` initialization to accept client connections.
- GUI components for the chat interface.
- Reading and writing threads for concurrent communication.

## Requirements

- Java Development Kit (JDK)
- Windows operating system

## Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/AragornKnight007/Windows_Based_Chat_App_In_JAVA.git

   ```

- Open the project in your preferred Java development environment.
- Run the Server class first and then run the Client class.
- Start chatting!

# Contributing
- Contributions to the project are welcome. Feel free to open issues or submit pull requests.

# License
- This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

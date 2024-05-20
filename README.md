# Go Chat Application with WebSockets

This repository contains a simple chat application built using Golang and WebSockets. The application allows multiple users to communicate in real-time through a WebSocket server.

## Features

- Real-time chat with WebSockets
- Simple HTML frontend
- Basic message broadcasting to all connected clients

## Getting Started

### Prerequisites

- [Go](https://golang.org/dl/) installed on your machine

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/AyhamJar/go-chat-application.git
    cd go-chat-application
    ```

2. Initialize the Go module and install dependencies:

    ```sh
    go mod init go-chat
    go get -u github.com/gorilla/websocket
    ```

### Usage

1. Run the Go server:

    ```sh
    go run main.go
    ```

4. Open your browser and navigate to `http://localhost:8080`. You should see the chat interface. Enter a username and a message, then click "Send". Open multiple browser tabs to see the real-time chat in action.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

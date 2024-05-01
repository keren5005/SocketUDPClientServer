
# SocketUDPClientServer

"SocketUDPClientServer" is a C++ project demonstrating UDP client-server communication using sockets. The client sends requests to the server, which responds with predefined messages. It's a simple example of socket programming in C++.

```
   _______         ___________         _______
  |       |  UDP  |           |  UDP  |       |
  | Client| <---->|   Network |<----->|Server |
  |_______|       |___________|       |_______|
```

## Overview

This project showcases a basic UDP client-server architecture where the client sends requests to the server, and the server responds accordingly. The client can send requests such as "how are you?", "how is the weather?", and "what is the time?", to which the server replies with appropriate responses.

## Features

- Simple UDP client-server communication.
- Server responds to client requests with predefined responses.
- Client can send different types of requests to the server.

## Instructions

### Prerequisites

- Windows operating system.
- Visual Studio or any C++ compiler installed.
- Basic knowledge of C++ programming.

### Setting Up

1. Clone this repository to your local machine:

```
git clone https://github.com/your_username/SocketUDPClientServer.git
```

2. Open the project in your preferred IDE or text editor.

3. Build the project using Visual Studio or compile the source files manually.

### Running the Application

1. Run the server application first. This will start the server and make it ready to accept client requests.

2. Run the client application. Follow the prompts to send requests to the server.

3. You can send requests such as:
   - `1` for "how are you?"
   - `2` for "how is the weather?"
   - `3` for "what is the time?"
   - `-1` to exit the client application.

4. The server will respond accordingly to each request from the client.

### Notes

- Make sure to have Winsock installed and properly configured on your system.
- The server is set to listen on port `27015`. Make sure this port is not used by any other application on your machine.
- Both client and server applications are configured to communicate on `localhost` (IP address `127.0.0.1`). You can modify this if needed.

## Contribution

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README according to your project's specific details and requirements!

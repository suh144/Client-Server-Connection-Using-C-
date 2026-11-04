# Client-Server-Connection-Using-C++
# C++ TCP Client-Server Application

A lightweight C++ socket programming project demonstrating a basic TCP/IP client-server connection on Windows using **Winsock2** (`ws2_32`). The server listens for incoming network connections on port 8080, and the client establishes a connection to transmit messages.

## Features

- **Socket Initialization:** Initializes and cleans up Winsock library (`WSAData`).
- **Server Architecture:** Binds to local port `8080`, listens for incoming requests, and accepts client connections.
- **Client Connection:** Connects over TCP to `127.0.0.1:8080` and sends string payloads.
- **Static Linking:** Standard C++ runtime libraries bundled via GCC static flags to avoid missing DLL dependencies.

## Prerequisites

- **Operating System:** Windows 10/11
- **Compiler:** MinGW-w64 (`g++`) with Winsock2 library support

## Compilation & Execution

Open two separate Command Prompt (or Terminal) windows and navigate to the project directory:

```cmd
cd "path\to\your\project"

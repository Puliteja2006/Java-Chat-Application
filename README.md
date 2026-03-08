# Java Client–Server Chat Application

A multi-client real-time chat application built using Java Socket Programming and Swing GUI.
This project demonstrates client–server architecture, multithreading, networking concepts, and GUI development.

The system allows multiple clients to connect to a centralized server, communicate in real time, send private messages, and view online users.


## Features:

✔ Multi-Client Server Architecture
✔ Real-Time Messaging
✔ Username Authentication
✔ Private Messaging (@username)
✔ Online Users List
✔ Join / Leave Notifications
✔ Chat History Persistence
✔ GUI Interface using Java Swing
✔ Multithreaded Server Handling Multiple Clients


## Architecture:

The application follows a Client–Server Architecture.

Clients (GUI)
   │
   │  Socket Communication
   ▼
Chat Server
   │
   ├── Manage Connected Clients
   ├── Broadcast Messages
   ├── Handle Private Messages
   └── Store Chat History

The server acts as a central communication hub, allowing multiple clients to interact simultaneously.


## Technologies Used:

Technology| Purpose
Java| Core programming language
Socket Programming| Client–Server communication
Multithreading| Handle multiple clients
Java Swing| Graphical User Interface
File Handling| Store chat history


## Project Structure:

ChatApplication
│
├── src
│   ├── server
│   │   ├── ChatServer.java
│   │   ├── ClientHandler.java
│   │   └── ChatHistory.java
│   │
│   └── client
│       └── ChatClientGUI.java
│
├── chat_history.txt
├── build.xml
└── README.md


## How to Run the Project:

1️⃣ Clone Repository

git clone https://github.com/puliteja2006/java-chat-application.git


2️⃣ Open in NetBeans

Open the project using Apache NetBeans IDE.


3️⃣ Start Server

Run:

ChatServer.java

Output:

Chat Server Started...


4️⃣ Start Clients

Run:

ChatClientGUI.java

You can open multiple clients to simulate multiple users.


## Example Usage:

Public message:

Hello everyone!

Private message:

@username Hello privately

Example:

@Teja Hi, this is a private message


## Key Concepts Demonstrated:

This project demonstrates several important software engineering and networking concepts:

• Client–Server Architecture
• TCP Socket Communication
• Multithreaded Server Design
• Event-Driven GUI Programming
• Message Broadcasting Systems
• Private Messaging Protocols


## Future Improvements:

Potential enhancements for this system:

• File Sharing Support
• Emoji & Rich Text Chat
• Group Chat Rooms
• Database Integration (MySQL)
• User Authentication System
• WebSocket Implementation with Spring Boot


## Author:

Puli Sai Srinivasa Teja

Aspiring Software Development Engineer (SDE)
Java Backend & Web Developer


## Support:

If you found this project useful:

⭐ Star this repository
🍴 Fork the project
💡 Contribute improvements.

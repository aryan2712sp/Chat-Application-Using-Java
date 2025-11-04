
# 💬 Java Client-Server Chat Application

![Java](https://img.shields.io/badge/Java-11%2B-orange?logo=java)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Console-lightgrey)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen)

A simple **Client-Server Chat Application** built using **Java Sockets**.  
This project demonstrates basic **TCP/IP communication** and **multithreading** concepts in Java, allowing real-time message exchange between a client and server.

---

## 🖼️ Project Preview

Server started...
Waiting for client connection...
Client connected!
Client: Hello Server!
Server: Hi Client! Welcome to the chat.

```

## 📁 Project Structure

```

📦 Java-Chat-App
├── Client.java
├── Client.class
├── Client$1.class
├── Server.java
├── Server.class
├── Server$1.class
└── README.md

````

---

## ⚙️ How It Works

- The **Server** starts and listens for incoming client connections on a specific port.  
- The **Client** connects to the server using a socket.  
- Once connected, both sides can **send and receive messages simultaneously** using threads.  
- The connection persists until either side closes the chat.

---

## 🚀 Getting Started

### 1️⃣ Compile the Source Code
```bash
javac Server.java Client.java
````

### 2️⃣ Start the Server

```bash
java Server
```

> The server will wait for a client to connect.

### 3️⃣ Start the Client (in another terminal or system)

```bash
java Client
```

Once both are connected, you can chat in real time!

---

## 💡 Features

✅ Real-time client-server communication
✅ Multi-threaded design (separate threads for sending & receiving)
✅ Lightweight and easy to understand
✅ Extensible for GUI or multi-client setups

---

## 🧩 Future Enhancements

🚀 Add multi-client chatroom support
💻 Create GUI using **Swing** or **JavaFX**
🔒 Implement message encryption
📂 Add file transfer functionality

---

## 🧠 Key Concepts Used

* `ServerSocket` and `Socket` (TCP communication)
* `InputStreamReader`, `BufferedReader`, and `PrintWriter` (data I/O)
* `Thread` & `Runnable` (multithreading)
* Exception handling and graceful shutdowns

---

## 📜 License

This project is licensed under the **MIT License** — feel free to modify and use it for learning or development purposes.
See the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Aryan Pardeshi**
📍 Pune, India
📧 [aryansp2712@gmail.com]
⭐ If you like this project, give it a **Star** on [GitHub](https://github.com/aryan2712sp)!


## 🔗 Useful Links

* [Java Socket Documentation](https://docs.oracle.com/javase/8/docs/api/java/net/Socket.html)
* [Oracle Java Tutorials - Networking](https://docs.oracle.com/javase/tutorial/networking/)

---


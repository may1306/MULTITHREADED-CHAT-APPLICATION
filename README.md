    # MULTITHREADED-CHAT-APPLICATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MAYUR SANJAY BHOYE

*INTERN ID*: CT06DZ57

*DOMAIN*: Java Programming

*DURATION*: 6 weeks

*MENTOR*: NEELA SANTHOSH

## DESCRIPTION OF TASK

1. Tools Used

The primary tool used in this project is the Java programming language along with its built-in networking and multithreading libraries. Some of the most important components include:

Java Sockets (java.net package):

ServerSocket is used on the server side to wait for incoming client connections.

Socket is used on the client side to connect to the server.
These classes establish a reliable TCP connection, enabling real-time data exchange.

Input/Output Streams (java.io package):
Communication between server and client is done using streams. For instance:

BufferedReader and InputStreamReader are used to read client messages.

PrintWriter is used to send messages back to the client.

Multithreading (java.lang package):
Since multiple clients need to communicate simultaneously, threads are created for each client connection. The ClientHandler class extends Thread or implements Runnable to run in parallel, ensuring that one client’s activities do not block others.

Java Compiler and Runtime:

javac (Java Compiler) compiles the .java source files into .class bytecode files.

java (Java Virtual Machine) executes the compiled classes, making the program platform-independent.

2. Editor Used

Several editors and IDEs (Integrated Development Environments) can be used to build and run this project:

Eclipse IDE: A widely used IDE for Java development, offering features like syntax highlighting, auto-completion, and debugging.

IntelliJ IDEA: Known for smart code suggestions, refactoring support, and a modern interface.

NetBeans IDE: An open-source IDE with simple project management tools, good for academic projects.

Visual Studio Code or Notepad++: Lightweight editors that can be paired with terminal compilation for those who prefer simplicity.

For this task, any of the above editors can be used effectively. Many students prefer Eclipse or IntelliJ IDEA because they make debugging multithreaded applications easier.

3. Platform Used

The platform for execution is the Java Development Kit (JDK) installed on an operating system. Since Java is platform-independent, the chat application can run on Windows, Linux, or macOS.

Development Environment:

JDK version 8 or above is recommended for socket programming.

JVM (Java Virtual Machine) ensures portability across systems.

Networking Environment:

The project can be tested locally using localhost and a port number (e.g., 1234).

It can also be deployed over a Local Area Network (LAN) or the Internet, where clients connect to the server using the server’s IP address.

4. Applications of the Task

The multithreaded chat application is not just an academic exercise; it has multiple real-world applications:

Educational Value:
This project helps students understand network programming, socket communication, concurrency, and client-server architecture. These are fundamental concepts in operating systems and computer networks courses.

Real-Time Messaging Systems:
The same principles are applied in large-scale chat systems like WhatsApp, Facebook Messenger, Slack, and Microsoft Teams. By extending the project with a GUI and database storage, it can evolve into a functional instant messaging app.

Corporate Communication:
Organizations can use custom-built chat applications for secure internal communication without relying on third-party software.

Online Gaming:
Multiplayer games often integrate real-time chat functionality using similar socket-based communication principles.

Customer Support Systems:
Many businesses use chat servers for live support between customers and service representatives, where multiple agents (clients) can communicate with the main server.

Distributed Systems and Cloud Computing:
This project introduces concepts of handling multiple client requests simultaneously, which is the foundation for designing scalable web servers and distributed cloud services.

## OUTPUT

<img width="1914" height="1008" alt="Image" src="https://github.com/user-attachments/assets/95cb5530-58e4-4f0e-b931-20043e925b1c" />


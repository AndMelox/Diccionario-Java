# Java Client-Server Translation Project

This project is a Java application for translating words from English to Spanish or French, developed with a client-server architecture that uses sockets and threads. Translation data is stored in JSON files, which the server reads and processes to respond to client requests.

## Key Features

- **Client-server architecture**: The server receives translation requests and returns the corresponding translation in the requested language (Spanish or French).
- **Sockets and threads**: Client-server communication is handled through sockets on port 9998, allowing simultaneous connections from multiple clients.
- **JSON for data storage**: Translations are stored in JSON files, making data organization and expansion easy.
- **Dependency management with Maven**: Project configuration and dependencies are managed through Maven, simplifying compilation and execution.

## Running the Program

To run the project, compile and package the JAR files with Maven. Once generated, ensure that the client and server folders are kept separate and outside of the repository. The JAR files can be executed from their respective `target` directories as follows:

1. Start the server:
    ```bash
    java -jar path/to/server/target/ServerDic.jar
    ```
2. Start the client:
    ```bash
    java -jar path/to/client/target/ClientDic.jar
    ```

The server should be running before starting the client. Communication occurs over port `9998`. The client can request the translation of an English word, and the server will respond with the translation in either Spanish or French, as requested.

## Requirements

- **Java**: version 8 or higher
- **Maven**: for managing and building the project

This project is ideal for understanding the use of sockets, multithreading, and client-server architecture in Java applications, as well as using JSON files for data storage.

## Authors

[<img alt="GitHub" src="https://img.shields.io/badge/GitHub-@AndMelox-181717?style=flat-square&logo=github">](https://github.com/AndMelox) 

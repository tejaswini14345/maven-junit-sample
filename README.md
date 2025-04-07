# Simple Maven JUnit Project

This project demonstrates how to create and run unit tests in a Java application using Maven and JUnit. It's a basic but powerful template for developers starting with Java test automation and build management using Maven.

## 🚀 Features

- Clean Maven project structure
- Unit testing with JUnit
- Easy to build, test, and package
- Simple example for beginners

## 🧰 Technologies Used

- **Java** (JDK 8 or higher)
- **JUnit** for unit testing
- **Apache Maven** for project build and dependency management

## 📁 Project Structure

maven/ ├── src/ │ ├── main/ │ │ └── java/ │ │ └── [Java source files] │ └── test/ │ └── java/ │ └── [JUnit test files] ├── pom.xml └── README.md


- `src/main/java`: Your main Java application code.
- `src/test/java`: JUnit test classes.
- `pom.xml`: Maven config file for dependencies and plugins.

## 🛠️ Getting Started

### Prerequisites

Make sure you have the following installed:

- [Java JDK 8+](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Apache Maven](https://maven.apache.org/download.cgi)

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/tejaswini14345/maven.git
cd maven

Compile the source :-  mvn compile

Compile the source :- mvn compile

Run tests :-  mvn test

Package the project :-  mvn package

Run the JAR file (if applicable) :-  java -jar target/your-jar-file-name.jar

Dependencies:-
<dependency>
    <groupId>junit</groupId>
    <artifactId>junit</artifactId>
    <version>4.13.2</version>
    <scope>test</scope>
</dependency>






# Java Hello World

A minimal Java Hello World project.

## Project Structure

```
Hello-Worlds-Project1/
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── example/
│                   └── HelloWorld.java
├── pom.xml
└── README.md
```

## Prerequisites

- Java 11+
- Maven 3.6+

## Run with Maven

```bash
mvn compile exec:java -Dexec.mainClass="com.example.HelloWorld"
```

## Compile & Run Manually

```bash
javac src/main/java/com/example/HelloWorld.java -d out
java -cp out com.example.HelloWorld
```


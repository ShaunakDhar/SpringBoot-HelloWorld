# SpringBoot HelloWorld

A simple Spring Boot project created using **Java 21**, **Maven**, and **Spring Boot 4.1.1**.

## Requirements

Before running the project, make sure you have:

- Git installed
- Java 21 installed
- Maven is optional because the project includes the Maven Wrapper

Check Java:

```bash
java -version
```

It should show Java 21.

---

## Clone the Project

Open Terminal / PowerShell and run:

```bash
git clone https://github.com/ShaunakDhar/SpringBoot-HelloWorld.git
```

Move into the project folder:

```bash
cd SpringBoot-HelloWorld
```

---

## Run the Project

### Windows

Using Maven Wrapper:

```powershell
.\mvnw.cmd spring-boot:run
```

### Linux / macOS

```bash
./mvnw spring-boot:run
```

If Maven is already installed globally, you can also run:

```bash
mvn spring-boot:run
```

---

## Run Using an IDE

You can also run the project using IntelliJ IDEA, Eclipse, or VS Code.

1. Clone the repository.
2. Open the `SpringBoot-HelloWorld` folder in your IDE.
3. Wait for Maven dependencies to download.
4. Open:

```text
src/main/java/com/example/demo/DemoApplication.java
```

5. Run `DemoApplication.java`.

The Spring Boot server will start.

By default, Spring Boot runs on:

```text
http://localhost:8080
```

---

## Getting the Latest Changes

If you have already cloned the repository and want the latest version:

```bash
git pull origin main
```

Then run the application again:

### Windows

```powershell
.\mvnw.cmd spring-boot:run
```

### Linux / macOS

```bash
./mvnw spring-boot:run
```

---

## Typical Workflow for a Friend

First time:

```bash
git clone https://github.com/ShaunakDhar/SpringBoot-HelloWorld.git
cd SpringBoot-HelloWorld
```

Then on Windows:

```powershell
.\mvnw.cmd spring-boot:run
```

For future updates:

```bash
git pull origin main
```

and restart the application:

```powershell
.\mvnw.cmd spring-boot:run
```

---

## Build the Project

To build the project without directly starting it:

### Windows

```powershell
.\mvnw.cmd clean package
```

### Linux / macOS

```bash
./mvnw clean package
```

The generated `.jar` file will be inside:

```text
target/
```

You can then run the JAR using:

```bash
java -jar target/demo-0.0.1-SNAPSHOT.jar
```

---

## Tech Stack

- Java 21
- Spring Boot 4.1.1
- Spring Web MVC
- Maven
- Git / GitHub

## Repository

```text
https://github.com/ShaunakDhar/SpringBoot-HelloWorld
```

# CHATBOT

A simple JavaFX desktop chatbot application built with Java and Maven.

## Project Overview

This project creates a small chat-style desktop app where users can:
- greet the bot
- ask for the time or date
- ask a trivia question
- request a joke
- convert currency
- set a budget or add an expense
- view a simple calendar
- perform basic arithmetic
- generate a random Gmail-style address

## Tech Stack

- Java 21
- JavaFX 17
- Maven
- org.json for JSON parsing

## Project Structure

- `src/main/java/org/example/chatbot/HelloApplication.java` - main application class and chat logic
- `src/main/java/org/example/chatbot/HelloController.java` - sample FXML controller
- `src/main/resources/org/example/chatbot/hello-view.fxml` - JavaFX FXML layout
- `src/main/java/module-info.java` - Java module declaration
- `pom.xml` - Maven dependencies and build configuration

## Run the Project

From the project root, run:

```bash
./mvnw clean javafx:run
```

## Notes

- The project uses JavaFX and requires a compatible JDK.
- The current configuration targets Java 21, which matches the installed JDK in this environment.
- Some features (such as joke and currency conversion) call external APIs over the network.

## Future Improvements

Possible improvements include:
- moving command logic into separate classes
- adding unit tests
- using asynchronous networking for API calls
- storing budget data persistently
- improving error handling and logging

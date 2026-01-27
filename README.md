# Snake Game (Java)

Simple Snake game built with Java Swing.

## How to Run

### Prerequisites

- Java JDK 8 or later installed
- Maven installed (and available on your `PATH`)

### Build and Run with Maven

From the `SnakeGame` directory:

```bash
mvn clean package
java -jar target/snake-game-1.0.0.jar
```

### Run without Maven (manual compile)

From the `SnakeGame` directory:

```bash
javac -d out src/main/java/snakegame/*.java
java -cp out snakegame.SnakeGame
```

## Controls

- Arrow keys: move the snake
- ENTER: restart after game over


# **Tic-Tac-Toe — Java Console Application**

This repository contains a straightforward and well-structured implementation of the classic 3×3 Tic-Tac-Toe game developed in Java. The program runs entirely in the console and demonstrates essential programming concepts such as array manipulation, input handling, conditional logic, and basic game-state evaluation.

---

## **Description**

The application enables two players to alternate turns by selecting numbered board positions. Each move is validated to ensure that the input is within range and that the chosen position is unoccupied. After every turn, the game evaluates the board for winning combinations—covering all rows, columns, and diagonals—and detects draw conditions when the board is full.

The codebase emphasizes clarity, readability, and maintainability, making it suitable for learners, demonstrations, or as a base for more advanced versions of the game.

---

## **Features**

* Two-player, turn-based console gameplay
* Input validation for invalid numbers and non-numeric entries
* Prevention of selecting occupied board positions
* Win detection across all standard Tic-Tac-Toe patterns
* Draw detection when no further moves remain
* Console board rendering after every move

---

## **How to Run**

1. Install Java (JDK 8 or newer).
2. Compile the program:

   ```bash
   javac Main.java
   ```
3. Run the program:

   ```bash
   java Main
   ```

---

## **File Structure**

```
Main.java     // Contains the full implementation of the game
```

---

## **Potential Enhancements**

* AI opponent using Minimax or heuristic strategies
* Graphical interface (JavaFX or Swing)
* Score tracking across multiple rounds
* Configurable board sizes
* Online multiplayer support

---



# Chess System in Java

This is a Java-based chess system project, organized into four packages: `Application`, `boardgame`, `chess`, and `pieces`. Each package plays a specific role in the project structure.

## Packages

### 1. Application
This package contains classes responsible for the main program logic and the user interface (UI). Here, user interactions are handled, ensuring a user-friendly experience.

### 2. boardgame
The `boardgame` package houses essential classes related to the board, pieces, and game position. This is where the foundation for game implementation is established.

### 3. chess
The `chess` package is crucial for the functioning of the game. The `ChessMatch` class controls the game, managing moves, checking victory conditions, and overseeing general game aspects.

### 4. pieces
In the `pieces` package, specific classes for each chess piece are found. Each class represents a unique piece, and its interactions with the board are defined here.

## Features

- **Piece Movement:** The system implements standard chess functionalities, allowing each piece to move according to established rules.

- **Captured Pieces Display:** Throughout the game, players can view the pieces captured by each opponent.

- **Possible Moves Highlight:** Before making a move, the system highlights possible positions for the selected piece on the board.

- **Special Moves:**
  - *Castling:* The system recognizes and allows the execution of castling if the conditions are met.
  - *En passant:* "En passant" moves are supported and implemented according to chess rules.
  - *Pawn Promotion:* If a pawn reaches the eighth rank, it can be promoted to another piece.

## Exception Handling

The system appropriately handles exceptions, especially in cases of attempting moves outside the chess rules. Error messages provide clear information to guide the user on the encountered issue.

---

# Chess Game (C & SDL2)

A 2D Chess game built from scratch in C using the SDL2 library. This project was created to practice modular programming and game logic.

## 🕹️ Features
- **Full Rules:** All pieces move according to standard chess rules.
- **Move Validation:** The game checks if a move is legal and handles "Check" and "Checkmate" states.
- **Drag & Drop:** Interactive interface for moving pieces with the mouse.
- **Pawn Promotion:** Automatically promotes pawns to Queens.

## 🛠️ Tech Stack
- **Language:** C
- **Libraries:** SDL2, SDL_image, SDL_ttf

## 🚀 How to Compile and Run
Make sure you have the SDL2 libraries installed, then run:

```bash
gcc main.c chess_logic.c -o chess -lSDL2 -lSDL2_image -lSDL2_ttf
./chess

# Console-Based Tic-Tac-Toe Game (C++)

A lightweight, interactive command-line implementation of the classic Tic-Tac-Toe game built using **C++**. This project demonstrates core computer science fundamentals, including matrix-grid manipulation, multi-conditional game loop state management, and algorithmic win-condition validation.

## 🛠️ Core Features
* **Matrix Grid Engine:** Utilizes a multidimensional array structure to seamlessly handle, track, and render the $3 \times 3$ game board updates in real-time.
* **Algorithmic Win-Checking:** Dynamically evaluates player moves across horizontal rows, vertical columns, and intersecting diagonals after every turn to detect wins or stalemate draws instantly.
* **Input Validation & Exception Prevention:** Features proactive console filtering to prevent runtime errors if a user inputs coordinates that are out-of-bounds or already occupied.
* **Interactive Two-Player Mode:** Alternates turn tracking state variables cleanly between Player 'X' and Player 'O'.

## 📊 Technical Architecture & Logic Workflow
The application follows a classic software engine game loop:



1. **Render:** The console updates and prints the updated $3 \times 3$ grid layout.
2. **Input Processing:** The system prompts the active player for row/column grid indices and verifies input safety.
3. **State Evaluation:** The engine checks for a winning combination or a maxed-out grid array (Stalemate / Draw).
4. **Context Switch:** The state flags alternate active players and repeat until a terminal state condition is achieved.

## 💻 Tech Stack & Concepts Applied
* **Language:** C++11 (or higher)
* **Data Structures:** Multidimensional Arrays / Matrices (`char board[3][3]`)
* **Control Flow:** Nested Conditional Statements, While-Loops, Function Modularization
* **Development Environment:** Linux Terminal Environment / VS Code

## 🏃‍♂️ How to Run Locally

### 1. Clone the repository
```bash
git clone [https://github.com/YOUR_USERNAME/Tic-Tac-Toe.git](https://github.com/YOUR_USERNAME/Tic-Tac-Toe.git)
cd Tic-Tac-Toe

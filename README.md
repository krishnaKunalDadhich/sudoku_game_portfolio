# 🧩 Sudoku Game – Professional Python Version

A beginner-friendly **Sudoku Game in Python** developed as part of my **Semester 2 Python Programming course**.  
This project demonstrates the practical application of **Python fundamentals, OOP, functions, file handling, and exception handling** in a single interactive game.

---

## 🚀 Features

- 🎮 Console-based Sudoku gameplay  
- ✅ Validates moves for rows, columns, and 3×3 subgrids  
- 🔄 Input validation with proper error handling  
- 💾 Save completed Sudoku board to a file (`completed_sudoku.txt`)  
- ⏱️ Timer: track how long it takes to finish the puzzle  
- 🟢 Difficulty Levels: Easy / Medium / Hard (JSON file integrated)  
- 🔧 Ready for extensions: GUI, Auto-solver, Leaderboard

---

## 📖 Why I Created This Project

This project was created to **apply syllabus concepts** practically at *Jodhpur Institute of Engineering & Technology (Autonomous, BTU Affiliated)*.  

It maps to Python course units as follows:

1. **Introduction to Python Programming**  
   - Learned variables, data types (numbers, strings, lists, dictionaries)  
   - Displayed Sudoku board with formatted printing  

2. **Python Operators and Control Flow**  
   - Used `if-else` conditions for input validation  
   - Loops (`for`, `while`) for board traversal and game logic  

3. **Data Structures, Functions & Packages**  
   - Nested lists for the Sudoku board  
   - Functions like `is_valid_move()` and `is_complete()`  
   - `time` module used for the game timer  

4. **Object-Oriented Programming (OOP)**  
   - Created `SudokuGame` class with encapsulated methods  
   - Applied instance methods for game logic  

5. **File I/O and Exception Handling**  
   - Saved completed board to a text file  
   - Handled invalid inputs gracefully

---

## 📂 Project Structure

sudoku_game_portfolio/
│── sudoku.py # Main Python game code
│── boards.json # Easy/Medium/Hard Sudoku boards
│── completed_sudoku.txt # Generated after saving a completed game
│── README.md # Project documentation
│── screenshots/ # Folder for game screenshots (optional)
│── .gitignore # Ignore unnecessary files like pycache


---

## ⚡ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/sudoku_game_portfolio.git
cd sudoku_game_portfolio

---

Run the game:

python sudoku.py


## Follow on-screen instructions to:

Choose difficulty

Enter row, column, and number

Save the completed board if desired

--- 

## 🎯 Future Scope

🔹 Add GUI using Tkinter or Pygame

🔹 Implement Auto-solver (Backtracking Algorithm)

🔹 Add leaderboard to store fastest completion times

🔹 Extend with more puzzles stored in JSON or database

---

## 📸 Screenshots

(Add console output screenshots here showing Easy, Medium, Hard boards, timer, and completed board)

---

## 👨‍💻 Author

Krishna Kunal Dadhich
B.Tech CSE, Semester 2
📧 [Your Email]
🔗 [LinkedIn / Portfolio link]

📜 License

This project is open-source and free to use for learning purposes.


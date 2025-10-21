# 🧮 Math Quiz Game

A simple **C++ console-based math game** that generates random math questions based on user-selected difficulty and operation type.  
The game tests the user's arithmetic skills through addition, subtraction, multiplication, and division questions — with multiple difficulty levels.

---

## 🎯 Features

- 🔢 Supports **Addition**, **Subtraction**, **Multiplication**, and **Division** (and a mixed mode).
- 🧠 Multiple difficulty levels:
  - Easy (1–10)
  - Medium (10–50)
  - Hard (50–100)
  - Mix (randomly chooses a level each time)
- 🎲 Randomly generated questions.
- 🧾 Tracks the number of correct and wrong answers.
- ✅ Displays a **final report** with performance summary.
- 🎨 Changes screen color depending on the result (green for correct, red for wrong).
- 🔁 Option to play again after finishing a quiz.

---

## 🧩 How It Works

1. The user is asked:
   - How many questions to answer.
   - What difficulty level to use.
   - What operation type to practice.
2. The game generates random math questions based on the user’s choices.
3. After answering all questions:
   - The program displays a detailed summary (correct, wrong, total).
   - Shows whether the user passed or failed.
4. The user can choose to play again.

---

## ⚙️ Technologies Used

- **Language:** C++
- **Compiler:** Any C++ compiler supporting C++11 or later
- **Libraries Used:**
  - `<iostream>` for input/output  
  - `<ctime>` and `<cstdlib>` for random number generation  

---

## 📁 Project Structure

```
Math-Quiz-Game/
│
├── main.cpp           # The main source code file
├── README.md          # Project documentation (you are reading it)
└── .vs/               # Visual Studio temporary files (ignored in Git)
```

> 📝 Tip: You can add a `.gitignore` file to exclude `.vs` or build folders.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the project in your IDE (Visual Studio, Code::Blocks, or any other C++ environment).
3. Compile and run:
   ```bash
   g++ main.cpp -o MathQuiz
   ./MathQuiz
   ```

---

## 📸 Example Output

```
How many Questions do you want to answer ? 3
Enter Questions Level [1] Easy, [2] Med, [3] Hard, [4] Mix ? 2
Enter Operation Type [1] Add, [2] Sub, [3] Mul, [4] Div, [5] Mix ? 5

Question [1/3]
12
6 +
__________
18
Right Answer :-)

Question [2/3]
25
4 -
__________
21
Right Answer :-)

Question [3/3]
30
5 /
__________
6
Right Answer :-)

-------------------------------
Final Result Is Pass :-)
-------------------------------
Number Of Questions : 3
Question Level : Mid
Op Type : Mix Operation
Number Of Right Answer : 3
Number Of Wrong Answer : 0
-------------------------------
```

---

## 🧠 Future Improvements

- Add **timer** for each question.  
- Add **score system** based on speed and accuracy.  
- Store high scores in a file.  
- Support **fractional division results**.  
- Build a **GUI version** with C++/Qt or SFML.

---

## 👨‍💻 Author

**Hossam Ahmed Ragab**  
📘 Student at Faculty of Computers and Information, El Shorouk Academy  
🎓 Following *Programming Advices Roadmap* by *Mohammed Abo Hadhoud*

---

⭐ *If you like this project, don’t forget to give it a star on GitHub!*

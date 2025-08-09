# 🎲 Math Operations Game – Console Application (C++)

## 🔹 Project Overview

**Math Operations Game** is an interactive console-based quiz application developed in C++. It challenges players to solve arithmetic questions generated dynamically based on chosen difficulty levels and operation types. The game offers a flexible and engaging way to practice basic math skills such as addition, subtraction, multiplication, and division.

Designed with clarity and modularity in mind, this project demonstrates fundamental programming concepts like enumerations, random number generation, input validation, and struct-based data management—all implemented in a clean and maintainable functional style.

---

## 🔹 Key Features & Deep Dive

### 1. Dynamic Question Generation

- **Difficulty Levels:**  
  Players can choose from four levels — *Easy*, *Medium*, *Hard*, or *Mixed*.  
  - *Easy* questions use numbers between 1 and 10.  
  - *Medium* questions use numbers between 10 and 50.  
  - *Hard* questions use numbers between 50 and 100.  
  - *Mixed* randomly selects any of the above levels per question.

- **Operation Types:**  
  The game supports five operation modes:  
  - Addition (+)  
  - Subtraction (-)  
  - Multiplication (x)  
  - Division (/)  
  - Mixed (randomly selects one operation per question)

- **Randomized Questions:**  
  Questions are generated at runtime with randomized operands and operations (if mixed), ensuring a unique gameplay experience every time.

### 2. User-Driven Customization

- Players specify the number of questions (between 1 and 10), preferred difficulty, and the operation type before starting.
- The program validates inputs and prompts until correct choices are made, enhancing robustness and user experience.

### 3. Structured Data Management

- Uses **structs** (`stQuestion` and `stQuizz`) to encapsulate all relevant data:
  - `stQuestion` stores operands, operation type, correct answer, user answer, and correctness status.
  - `stQuizz` manages the collection of questions, tracks the number of right/wrong answers, quiz settings, and pass/fail result.

### 4. Real-Time Feedback & UI Enhancement

- After each answer, the player immediately receives feedback:
  - Correct answers keep the screen color green.
  - Wrong answers trigger a red screen color with a beep alert and display the correct answer.
- The use of console color changes (`system("color XY")`) visually engages the player and improves accessibility.

### 5. Pass/Fail Evaluation

- The game computes the final result based on the number of correct versus incorrect answers.
- Passing requires at least as many correct answers as wrong ones.
- Detailed summary shows number of questions, difficulty level, operation type, and counts of correct/incorrect answers.

### 6. Replayability

- After finishing a quiz, players can choose to replay or exit.
- The quiz resets cleanly with screen clearing and color reset, providing a smooth continuous experience.

---

## 🔹 Technologies & Concepts Used

- **Language:** C++
- **Programming Paradigm:** Procedural / Functional Programming
- **Core Concepts:**  
  - Enumerations (`enum`) for managing difficulty levels and operation types  
  - Random number generation (`rand()`) for dynamic question creation  
  - Structs for organizing quiz and question data  
  - Input validation loops  
  - Console manipulation for color and sound feedback  
  - Modular function decomposition for clarity and maintainability

---

## 🔹 How to Play

1. Run the program.
2. Enter how many questions you want to answer (up to 10).
3. Select your desired difficulty level: Easy, Medium, Hard, or Mix.
4. Choose the type of operation: Add, Subtract, Multiply, Divide, or Mix.
5. Answer the questions one by one.
6. Receive immediate feedback on each answer.
7. After completing the quiz, view your final score and pass/fail status.
8. Choose to play again or exit.

---

## 🔹 Why This Project Matters

This game is a practical exercise that highlights:

- Effective use of C++ language fundamentals in a real-world scenario.
- Implementing user interaction and input validation.
- Dynamic data-driven content generation.
- Combining program logic with basic UI/UX enhancements using console colors and sounds.
- Structuring code cleanly with clear separation of concerns and reusable functions.

It is a solid foundation project ideal for learners wanting to improve programming logic, practice C++ syntax, and understand game loops and state management.

---

## 🔹 Repository Link

[Project-Math-Operations-Game GitHub Repository](https://github.com/your-username/Project-Math-Operations-Game)

---

## 📩 Contact

Feel free to connect with me for questions, feedback, or collaboration on [LinkedIn](www.linkedin.com/in/zakaria-sakalli-housaini-1a782b289).

---

> *Developed by a passionate learner focused on crafting clean, engaging, and educational C++ applications.*

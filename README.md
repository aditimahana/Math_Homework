# Math Homework 🧮

## 📖 Introduction

This project is a beginner Python exercise from Section 3 of *Teach Your Kids to Code*. It introduces `while` loops and repeated user interaction through a simple mathematical expression evaluator.

The program allows users to enter mathematical expressions, calculates their answers, and continues accepting new expressions until the user chooses to quit.

## 🖥️ Program Overview

### MathHomework.py

**What it does:**
1. Displays the program name.
2. Asks the user to enter a mathematical expression.
3. Evaluates the expression and displays the answer.
4. Prompts the user to enter another expression.
5. Repeats the process until the user enters `q`.

**Expected output:**

```text
MathHomework.py
Enter a math problem, or 'q' to quit: 5 + 3
The answer to 5 + 3 is: 8

Enter another math problem, or 'q' to quit: 12 * 4
The answer to 12 * 4 is: 48

Enter another math problem, or 'q' to quit: q
```

The program keeps running until the user enters `q`.

## 🛠️ What I Learned

- **User input:** Collecting mathematical expressions using `input()`.
- **While loops:** Repeating instructions while a condition remains true.
- **Conditions:** Checking whether the user has entered the quit command.
- **Expression evaluation:** Using `eval()` to evaluate mathematical expressions.
- **Loop control:** Creating an exit condition to prevent an endless loop.
- **Program flow:** Understanding how instructions repeat and interact with user input.

## 🚀 How to Run

1. Install Python.
2. Clone or download this repository.
3. Open the project folder in your Python IDE.
4. Run the program:

```bash
python MathHomework.py
```

Enter a mathematical expression to calculate its answer. Type `q` when you want to exit.

**Note:** This is a learning exercise using `eval()`. In real-world applications, avoid evaluating untrusted input with `eval()`, as it can execute arbitrary code.

## 📚 Credits

This exercise is based on Section 3 of *Teach Your Kids to Code* by Bryson Payne.

The program was completed as part of my Python learning journey.

---

**Course:** *Teach Your Kids to Code*  
**Section:** 3  
**Language:** Python

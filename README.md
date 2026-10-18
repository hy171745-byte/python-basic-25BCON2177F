# Fibonacci Series Generator in Python

## 📌 Overview

This project demonstrates how to generate the **Fibonacci series** using Python. The program uses a `for` loop and variable updates to print the first 10 terms of the sequence.

In the Fibonacci series, each number after the first two is the sum of the previous two numbers.

## 🎯 Objectives

- Understand the Fibonacci sequence.
- Learn how to use `for` loops in Python.
- Practice variable initialization and updating.
- Understand basic arithmetic operations and sequence generation.

## 💻 Source Code

```python
n = 10
a = 0
b = 1

for i in range(n):
    print(a, end=" ")

    next = a + b
    a = b
    b = next
```

## ⚙️ How It Works

1. **Initialize variables:** `a = 0` and `b = 1` represent the first two Fibonacci numbers.
2. **Repeat the loop:** `range(n)` runs the loop 10 times.
3. **Print the current term:** The program prints the value of `a`.
4. **Calculate the next term:** Add `a` and `b` and store the result in `next`.
5. **Update the variables:** Assign `b` to `a` and `next` to `b`.
6. **Continue:** Repeat until all 10 terms have been printed.

## 📤 Output

```text
0 1 1 2 3 5 8 13 21 34
```

## 🧮 Fibonacci Sequence

The sequence begins with 0 and 1. Each subsequent number is calculated by adding the previous two numbers.

For example:

- 0 + 1 = 1
- 1 + 1 = 2
- 1 + 2 = 3
- 2 + 3 = 5

## 🛠️ Requirements

- Python 3.x
- Any Python editor, such as VS Code, PyCharm, or Google Colab.

No external libraries are required.

## ▶️ How to Run

1. Copy the source code into a file named `fibonacci.py`.
2. Open a terminal in the project directory.
3. Run the following command:

```bash
python fibonacci.py
```

You can also execute the program directly in Google Colab.

## ⏱️ Complexity Analysis

- **Time Complexity:** `O(n)` — the loop runs `n` times.
- **Auxiliary Space Complexity:** `O(1)` — the algorithm uses a constant number of variables.

## 🚀 Future Improvements

- Accept the number of terms from the user.
- Add input validation for negative values.
- Display each Fibonacci number on a separate line.
- Extend the program to calculate the Fibonacci number at a specific position.

## 📚 Concepts Covered

Python variables, `for` loops, arithmetic operations, sequence generation, and time and space complexity.

## 👨‍💻 Author

Created as a beginner-friendly Python programming exercise.

---

⭐ If you find this project useful, consider giving the repository a star.

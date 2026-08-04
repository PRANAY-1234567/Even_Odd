# 🔢 Even or Odd Number Checker in JavaScript

A simple JavaScript program that determines whether a given number is **Even** or **Odd** using the modulus (`%`) operator. The project demonstrates the use of functions, conditional statements, and basic arithmetic operations in JavaScript.

This project is ideal for beginners learning JavaScript fundamentals.

---

# 📌 Overview

The program defines a function named `checkEvenOdd()` that accepts a number as input and returns:

* **"Even"** if the number is divisible by **2**
* **"Odd"** if the number is not divisible by **2**

The function is then tested with sample numbers using `console.log()`.

---

# 🚀 Features

* Checks whether a number is even or odd
* Uses a reusable JavaScript function
* Demonstrates the modulus (`%`) operator
* Simple and beginner-friendly code
* Displays output in the browser console or Node.js terminal

---

# 🛠️ Technologies Used

* JavaScript (ES6)

---

# 📂 Project Structure

```text
Even-Odd-Checker/
│
├── evenOdd.js
└── README.md
```

---

# 💻 Source Code

```javascript
function checkEvenOdd(num) {
  if (num % 2 === 0) return "Even";
  return "Odd";
}

console.log(checkEvenOdd(3));
console.log(checkEvenOdd(4));
```

---

# ▶️ How to Run

## Using Node.js

```bash
node evenOdd.js
```

## Using a Browser

1. Create an HTML file.
2. Link the JavaScript file or paste the code inside a `<script>` tag.
3. Open the browser.
4. View the output in the Developer Console (`F12` → Console).

---

# 📋 Sample Output

```text
Odd
Even
```

---

# 🧠 Concepts Covered

* JavaScript Functions
* `if` Statement
* Modulus (`%`) Operator
* `return` Statement
* Console Output
* Basic Number Operations

---

# 🔍 How It Works

1. Define a function named `checkEvenOdd()`.
2. Pass a number as the function argument.
3. Check whether the number is divisible by `2` using the modulus operator.
4. Return `"Even"` if the remainder is `0`.
5. Otherwise, return `"Odd"`.
6. Print the returned value using `console.log()`.

---

# 📖 Algorithm

1. Start the program.
2. Create a function that accepts a number.
3. Check if `num % 2 === 0`.
4. If true, return `"Even"`.
5. Otherwise, return `"Odd"`.
6. Call the function with sample values.
7. Display the results.
8. End the program.

---

# ⏱️ Complexity Analysis

| Operation        | Complexity |
| ---------------- | ---------- |
| Time Complexity  | **O(1)**   |
| Space Complexity | **O(1)**   |

---

# 🔮 Future Improvements

* Accept user input using `prompt()`
* Validate numeric input
* Check multiple numbers using arrays
* Generate random numbers and determine parity
* Build a web interface with HTML and CSS
* Extend the program to classify positive/negative numbers

---

# 🎯 Learning Outcomes

After completing this project, you will understand:

* How JavaScript functions work
* Using conditional statements for decision-making
* The modulus operator for divisibility checks
* Returning values from functions
* Displaying output using `console.log()`

---

# 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer

Aspiring Software Engineer | JavaScript | Python | Java | SQL | Data Analytics

---

# 📄 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and contribute for educational and learning purposes.

---

⭐ If you found this project helpful, don't forget to **Star** the repository!

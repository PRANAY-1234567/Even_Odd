🔢 Even or Odd Number Checker (JavaScript)

📌 Description

This program checks whether a given number is Even or Odd using JavaScript.

An even number is divisible by 2, while an odd number is not.

🧩 Problem Statement

Given a number, determine:

If it is divisible by 2 → Even

Otherwise → Odd

✅ Code
function checkEvenOdd(num) {
  if (num % 2 === 0) return "Even";
  return "Odd";
}

console.log(checkEvenOdd(5));

🧠 Explanation

The function checkEvenOdd() takes a number as input

The % operator gives the remainder after division

If num % 2 === 0, the number is divisible by 2 → Even

Otherwise, it is → Odd

The result is printed using console.log()

🖨 Example Output
Odd

🛠 Concepts Used

Functions in JavaScript

Conditional statements (if)

Modulus operator (%)

Console output

🎯 Use Cases

Beginner JavaScript practice

Interview preparation

Basic number logic problems

Learning functions and conditions

🚀 Possible Improvements

Take user input from prompt

Check multiple numbers in a loop

Add error handling for invalid input

👨‍💻 Author

Pranay Jadhao

# 🧠 Java Recursion — Top 50 Practical Questions

<div align="center">

### 🔁 Master Recursion. Build Logic. Ace Practicals.

A collection of **50 carefully selected recursion programs in Java**, designed for **college practicals, lab examinations, viva preparation, and programming practice**.

<br>

![Java](https://img.shields.io/badge/Java-Programming-orange?style=for-the-badge\&logo=openjdk\&logoColor=white)
![Recursion](https://img.shields.io/badge/Topic-Recursion-blue?style=for-the-badge)
![Programs](https://img.shields.io/badge/Programs-50-success?style=for-the-badge)
![Beginner Friendly](https://img.shields.io/badge/Level-Beginner--Intermediate-purple?style=for-the-badge)

</div>

---

## ✨ About This Repository

This repository contains **50 recursion-based practical programs written completely in Java**.

Every program is designed with:

* ⌨️ **User-defined input**
* 🔁 **Recursive functions**
* 🧩 **Simple and understandable logic**
* 🎓 **Practical-exam friendly code**
* 💡 **Beginner-friendly implementation**

The goal is simple:

> **Understand the logic behind recursion instead of just memorizing programs.**

---

## 🔥 What's Inside?

| #  | Topic                         | Programs |
| -- | ----------------------------- | -------: |
| 01 | 🔢 Basic Number Recursion     |      1–5 |
| 02 | 🔍 Digit-Based Recursion      |     6–10 |
| 03 | 🧮 Mathematical Recursion     |    11–17 |
| 04 | 🔢 Number Patterns            |    18–20 |
| 05 | 📦 Array Recursion            |    21–26 |
| 06 | 🔤 String Recursion           |    27–30 |
| 07 | 📊 Practical Utility Problems |    31–36 |
| 08 | ⭐ Patterns & Array Searching  |    37–41 |
| 09 | 🔢 Digit & Array Operations   |    42–48 |
| 10 | 🎨 Recursive Patterns         |    49–50 |

---

# 📚 Top 50 Programs

### 🔢 Basic Recursion

* 1. Print numbers from `1 to n`
* 2. Print numbers from `n to 1`
* 3. Sum of first `n` natural numbers
* 4. Factorial of a number
* 5. Power of a number

### 🔍 Number & Digit Recursion

* 6. Count digits of a number
* 7. Sum of digits
* 8. Reverse a number
* 9. Check palindrome number
* 10. Fibonacci series
* 11. Check prime number
* 12. GCD of two numbers
* 13. LCM of two numbers
* 14. Decimal to binary
* 15. Product of digits
* 16. Sum of even numbers
* 17. Sum of odd numbers
* 18. Print even numbers
* 19. Print odd numbers
* 20. Count zero digits

### 📦 Array Recursion

* 21. Sum of array elements
* 22. Maximum element in array
* 23. Minimum element in array
* 24. Reverse an array
* 25. Check array palindrome
* 26. Search an element
* 32. Sum of elements at even positions
* 38. Count occurrences
* 39. First occurrence
* 40. Last occurrence
* 41. Reverse array printing
* 44. Product of array elements
* 45. Average of array
* 48. Minimum element in array

### 🔤 String Recursion

* 27. Count digits in string
* 28. Reverse a string
* 29. Find string length
* 30. Count vowels
* 43. Count consonants

### 🧮 Mathematical & Utility Recursion

* 31. Multiplication table
* 33. Print digits
* 34. Count even digits
* 35. Digital root / repeated digit sum
* 36. Steps to reduce number to zero
* 42. Sum of odd digits
* 46. Binary to decimal
* 47. Sum of prime digits
* 50. Sum between two numbers

### 🎨 Recursive Patterns

* 37. Star pattern
* 49. Number pattern

---

# 🧩 Understanding Recursion

Recursion is a technique where a **function calls itself** to solve a smaller version of the same problem.

Every recursive solution generally contains two important parts:

```java
static int sum(int n) {

    // Base Case
    if (n == 0)
        return 0;

    // Recursive Case
    return n + sum(n - 1);
}
```

### 🛑 Base Case

The condition that **stops the recursion**.

```java
if (n == 0)
    return 0;
```

### 🔁 Recursive Case

The function calls itself with a **smaller or simpler input**.

```java
return n + sum(n - 1);
```

---

# 🌳 Recursion Visualization

For:

```text
sum(5)
```

The function calls itself like this:

```text
             sum(5)
                │
             sum(4)
                │
             sum(3)
                │
             sum(2)
                │
             sum(1)
                │
             sum(0)
                │
               0
```

Then the values return upward:

```text
sum(0) = 0
sum(1) = 1
sum(2) = 3
sum(3) = 6
sum(4) = 10
sum(5) = 15
```

---

# ⚡ Quick Recursion Cheat Sheet

### Number → `n - 1`

```java
function(n - 1);
```

### Digits → `n / 10`

```java
function(n / 10);
```

### Array → `n - 1`

```java
function(a, n - 1);
```

### String → `i + 1`

```java
function(s, i + 1);
```

### Two Ends → `start + 1`, `end - 1`

```java
function(a, start + 1, end - 1);
```

---

# 🛠️ Technologies Used

```text
☕ Java
🔁 Recursion
⌨️ Scanner
📦 Arrays
🔤 Strings
🧮 Mathematical Logic
```

---

# ▶️ How to Run

### 1️⃣ Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
```

### 2️⃣ Open the project

Open the project in:

* IntelliJ IDEA
* Eclipse
* VS Code
* NetBeans

### 3️⃣ Compile

```bash
javac Main.java
```

### 4️⃣ Run

```bash
java Main
```

### 5️⃣ Enter your own input

Example:

```text
Enter n: 5

1 2 3 4 5
```

---

# 🎯 Learning Goals

By completing these programs, you can practice:

* ✅ Understanding base cases
* ✅ Understanding recursive calls
* ✅ Tracing recursive functions
* ✅ Number recursion
* ✅ Digit recursion
* ✅ Array recursion
* ✅ String recursion
* ✅ Searching using recursion
* ✅ Mathematical recursion
* ✅ Pattern generation
* ✅ Problem-solving skills

---

# 🎓 Perfect For

```text
📚 College Practicals
🧪 Lab Examinations
🎤 Viva Preparation
💻 Java Practice
🧠 DSA Fundamentals
🔁 Recursion Practice
```

---

# 📈 Difficulty Progression

```text
Beginner
   │
   ├── Basic Number Recursion
   │
   ├── Digit Recursion
   │
   ├── Mathematical Recursion
   │
   ├── Array Recursion
   │
   ├── String Recursion
   │
   └── Recursive Patterns
          │
          ▼
   Beginner → Intermediate
```

---

# 💡 Practical Exam Tip

When you see a recursion question, think in this order:

```text
        ┌─────────────────────┐
        │  1. What is the     │
        │     smallest case?  │
        └──────────┬──────────┘
                   ↓
        ┌─────────────────────┐
        │  2. Write the      │
        │     base case       │
        └──────────┬──────────┘
                   ↓
        ┌─────────────────────┐
        │  3. Make the input │
        │     smaller         │
        └──────────┬──────────┘
                   ↓
        ┌─────────────────────┐
        │  4. Call the same  │
        │     function        │
        └──────────┬──────────┘
                   ↓
        ┌─────────────────────┐
        │  5. Return / print  │
        │     the result      │
        └─────────────────────┘
```

> **Base Case → Smaller Problem → Recursive Call → Result**

---

# ⭐ Repository Highlights

```text
50
│
├── 🔢 Number Problems
├── 🧮 Mathematical Problems
├── 📦 Array Problems
├── 🔤 String Problems
├── 🔍 Searching Problems
├── 🎨 Pattern Problems
└── 🔁 Recursion Fundamentals
```

---

## 🚀 Keep Practicing

Recursion becomes easier when you stop thinking about **all recursive calls at once**.

Focus on:

> **“What is the smallest problem I can solve, and how can I reduce the current problem to it?”**

That's the core idea behind recursion. 🔁

---

<div align="center">

### ☕ Code. 🔁 Recurse. 🧠 Understand. 🚀 Improve.

**Made for learning Java recursion one problem at a time.**

</div>

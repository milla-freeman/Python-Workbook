# 🐍 Python Fundamentals Project  
### Loops • Conditionals • Functions • Data Types • ATM Program • Practice Exercises

---

## 📌 Project Overview

This repository contains my Python learning journey completed during the Data Technician Bootcamp.  
The work covers Python fundamentals, small practical scripts, and a full mini-project simulating an ATM system using functions, loops and conditionals.

The purpose of this project was to build confidence in writing Python code from scratch and applying it to real problem-solving tasks.

---

## 🛠️ Skills Practised

### **🔹 Core Python Concepts**
- Variables and data types  
- User input  
- Strings and lists  
- Arithmetic operators  
- Conditional statements (`if`, `elif`, `else`)  
- Loops (`for`, `while`)  
- Functions and functional structure  
- Basic data validation  

---

## 🧮 FizzBuzz Program

Implemented the classic interview task:

- Print numbers 1 to 100  
- “fizz” for multiples of 3  
- “buzz” for multiples of 5  
- “fizzbuzz” for multiples of both  
- Otherwise print the number  

Example snippet:

```python
for i in range(1, 101):
    if i % 3 == 0 and i % 5 == 0:
        print("fizzbuzz")
    elif i % 3 == 0:
        print("fizz")
    elif i % 5 == 0:
        print("buzz")
    else:
        print(i)
````

---

## 🏧 ATM Mini-Project

A full Python program that simulates an ATM:

* Main menu system
* View balance
* Withdraw money
* Deposit money
* Optional PIN verification
* Validation checks (multiples of 10, insufficient funds, etc.)
* Reusable functions for each feature
* Looping menu until user chooses to exit

Example structure:

```python
def show_balance():
    print(f"Your balance is £{balance}")

def withdraw():
    # logic with multiple options
    pass

def deposit():
    # logic for user deposit
    pass

# Main loop
while True:
    print("1. View Balance")
    print("2. Withdraw")
    print("3. Deposit")
    print("4. Exit")
    
    choice = input("Choose an option: ")
    # execute based on choice
```

This exercise demonstrates control flow, function design, input handling and user interaction.

---

## 📚 Additional Practice

Completed recommended extra learning:

* Kaggle Pandas tutorial
* Kaggle Data Visualisation course
* Additional Python challenges
* HackerRank Python exercises
* CodingChef practice problems

---

## 🧰 Tools Used

* **Python 3**
* **Google Colab**
* **Jupyter Notebook**

---

## 📝 Reflection

Through this project I strengthened my ability to:

* Write clean, structured Python code
* Use functions, loops, and conditions effectively
* Build small programs from scratch
* Combine user input with logic
* Solve common beginner/intermediate Python challenges

This foundational knowledge supports my progression toward data analysis, scripting and automation tasks.

---

## 🚀 Future Improvements

* Add file handling and data storage to the ATM project
* Rewrite scripts using object-oriented programming
* Use Python with real datasets (CSV, Excel, JSON)
* Create visualisations with `matplotlib` or `seaborn`
* Build a more advanced Python mini-project

---


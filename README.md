# ☕ Coffee Machine (OOP) — Day 16 of #100DaysOfCode Python

### *My first Object-Oriented Programming project in Python*

Welcome to **Day 16** of my *100 Days of Python* journey!
This project marks a huge milestone for me because it’s the **first time I built something using Object-Oriented Programming (OOP)**. The goal was to take a previously procedural “coffee machine” script and **refactor it into clean, structured, reusable OOP code**.

---

## 🚀 Project Overview

This Coffee Machine program simulates a real-world coffee machine.
Users can order drinks like **espresso**, **latte**, or **cappuccino**, insert coins, and the machine will check resources, process payments, and make the drink.

What makes this version special is that the whole machine is built using **classes**, **objects**, and **methods**, demonstrating core OOP concepts:

* **Encapsulation**
* **Abstraction**
* **Composition**
* **Modular design**

---

## 🧠 What I Learned

This project helped me understand and apply:

### ✔️ Classes & Objects

I created and used classes like:

* `CoffeeMaker`
* `MoneyMachine`
* `MenuItem`
* `Menu`

### ✔️ Responsibility Separation

Each class has a specific job:

* The **CoffeeMaker** handles water/milk/coffee usage
* The **MoneyMachine** manages payments and tracks profit
* The **Menu** handles drink options
* The **MenuItem** represents each type of coffee

### ✔️ Cleaner, More Scalable Code

Instead of one giant mess of functions, everything is modular.
Adding a new drink or changing prices is now super simple.

---

## 🧩 Project Structure

```
.
├── main.py
├── coffee_maker.py
├── money_machine.py
├── menu.py
└── README.md
```

---

## 🕹️ How the Program Works

1. Run the program.
2. You’ll be prompted to choose a drink:

   * **espresso**
   * **latte**
   * **cappuccino**
3. The machine checks whether it has enough resources.
4. If yes, it asks for payment.
5. Once paid successfully, your drink is “made”.
6. You can also type:

   * `report` → Shows current resources and money
   * `off` → Shuts down the machine

---

## 🛠️ How to Run It

Make sure you have Python 3 installed.
Then run:

```bash
python main.py
```

No external packages required.

---

## 📦 Features

### ☕ Make Coffee

Choose from a menu of drinks.
The machine checks ingredients and processes the order.

### 💰 Payment System

Insert:

* Quarters
* Dimes
* Nickels
* Pennies

The program calculates:

* Total inserted
* Change to return
* Profit made

### 📊 Reports

Shows current resource levels + total money earned.

### 🔌 Machine Control

Admin command:

* `off` = safely shut down the machine

---

## 🧱 Core OOP Classes (High-Level Breakdown)

### **class MenuItem**

Represents a single drink with:

* Name
* Cost
* Water/Milk/Coffee requirements

### **class Menu**

Holds all drink options and returns selected items.

### **class CoffeeMaker**

Responsible for:

* Tracking resources
* Checking ingredient availability
* Making the drink

### **class MoneyMachine**

Handles:

* Coin processing
* Payment verification
* Tracking profit

---

## 📘 Example Interaction

```
What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
How many quarters?: 8
How many dimes?: 0
How many nickels?: 0
How many pennies?: 0
Here is $0.50 in change.
Making your latte... ☕
Enjoy!
```

---

## 🎯 Final Thoughts

This project helped me truly understand *how powerful OOP is*.
Instead of spaghetti code, everything is clean and separated.
It gave me the foundation to build bigger, more complex applications in the future.

### ⭐ This was the day I started thinking like a real developer.


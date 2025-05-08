# ☕ OOP Digital Coffee Machine in Python

Welcome to Day 16 of my #100DaysOfCode challenge!

In this project, I refactored my Day 15 Digital Coffee Machine into a fully modular, Object-Oriented Program using Python. This version simulates a real coffee vending machine with classes, methods, and cleaner file structure.

## 🔧 What I Learned

- Python OOP concepts (Classes, Objects, Methods)
- Creating modular and reusable code
- Organizing a multi-file project like real-world applications
- User input handling and currency simulation (Rupees 🇮🇳)

## 🗂️ Project Structure

oop-digital-coffee-machine-python/
├── coffee_maker.py # Handles water, milk, and coffee resources
├── main.py # Main program logic & user interaction
├── menu.py # Menu class for drink options
├── money_machine.py # Handles rupee-based payment system
└── README.md # You're reading it 😉

## ▶️ How It Works

- User chooses a drink: `latte`, `espresso`, or `cappuccino`
- Machine checks for resources
- Accepts payment using ₹ coins (₹10, ₹5, ₹2, ₹1)
- If enough money is inserted, it dispenses coffee and returns change

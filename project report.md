---
title: "Grocery Inventory Management System"
subtitle: "Console-Based Inventory Tracker using Python"
author: "[Your Full Name]"
date: "Submission Date: November 2025"
geometry: margin=1in
fontsize: 12pt
---

# Cover Page

**Project Title**  
**Grocery Inventory Management System**  
*A Simple Console-Based Inventory Tracker using Python*

**Submitted by:**  
[Your Full Name]  
[Your Roll Number / ID]  
[Your Class / Batch]

**Course:** Python Programming / Introduction to Programming  
**Submitted to:** [Teacher / Professor Name]  
**Date of Submission:** November 2025

---

# 1. Introduction
This project is a simple yet functional **Grocery Inventory Management System** developed using core Python. It helps small shop owners track stock levels, add new items, record sales/restocking, identify low-stock items instantly, and calculate the total value of inventory — all through an easy text-based menu.

The system uses only built-in Python features (no external libraries), making it lightweight, portable, and ideal for learning fundamental programming concepts such as dictionaries, functions, loops, conditionals, and error handling.

---

# 2. Problem Statement
Small grocery stores and local vendors usually track inventory manually using registers or Excel sheets. This leads to:
- Human errors in stock counting
- Difficulty identifying low-stock items quickly
- No real-time total value calculation
- Time-consuming updates during restocking or sales

This project provides a digital, error-resistant, and fast solution using a menu-driven Python program.

---

# 3. Functional Requirements
1. Add a new grocery item with name, price, and quantity
2. Update stock quantity (increase for restock, decrease for sale)
3. Prevent stock from going negative
4. Display full inventory in a formatted table (sorted alphabetically)
5. Highlight items with quantity < 10 (low stock alert)
6. Calculate and display total monetary value of all items
7. Provide a clean interactive menu (1–5 options)

---

# 4. Non-Functional Requirements
- Simple and intuitive user interface
- Fast execution (in-memory operations)
- Input validation and meaningful error messages
- No external dependencies
- Cross-platform compatibility (Windows, macOS, Linux)
- Beginner-friendly and readable code

---

# 5. System Architecture
The system follows a **procedural architecture** with:
- A global dictionary (`inventory`) acting as the in-memory database
- Separate functions for each operation (add, update, display, calculate)
- A central `menu()` loop controlling program flow
- Direct user interaction via `input()` and `print()`

# Project Statement - Grocery Inventory Management System

### Problem Statement
Small grocery stores and local shops often manage their inventory manually using notebooks or spreadsheets, which is time-consuming and prone to errors. There is a need for a simple, lightweight, and easy-to-use digital tool that allows shopkeepers to:
- Track stock levels of grocery items in real-time  
- Quickly add new products and update quantities when items are received or sold  
- Get instant alerts when any item is running low  
- Know the total monetary value of the current stock  

This project solves these issues by providing a console-based inventory management system built using core Python concepts.

### Scope of the Project
The system is designed as a minimal viable inventory tool suitable for educational purposes and small-scale real-world use. It includes:
- In-memory storage of items (using Python dictionary)  
- Basic CRUD-like operations: Add item, Update quantity  
- Automatic low-stock detection and visual alerts  
- Calculation of total inventory value  
- Menu-driven user interface with input validation  

**Out of scope (intentionally not included):**  
- Persistent storage (saving to file/database)  
- User authentication  
- Barcode scanning or advanced reporting  
- Multi-user support  

### Target Users
- Small grocery shop owners  
- Kirana/dukan storekeepers  
- Students learning Python programming  
- Beginners practicing console-based applications  
- Anyone who needs a simple inventory tracker without complex software

### High-Level Features
1. **Add New Item**  
   Add a grocery item with name, unit price, and initial quantity.

2. **Update Stock Quantity**  
   Increase stock (restock) or decrease stock (sale/adjustment). Prevents negative stock.

3. **View Full Inventory**  
   Displays all items in a formatted table (sorted alphabetically) with price, quantity, and stock status (OK / LOW).

4. **Low Stock Alert System**  
   Automatically flags items with quantity < 10 and shows count of items needing restock.

5. **Total Inventory Value Calculation**  
   Computes and displays the total worth of all items currently in stock.

6. **User-Friendly Menu Interface**  
   Simple numbered menu (1–5) with clear prompts and error messages for invalid inputs.

This project demonstrates practical use of Python dictionaries, functions, loops, conditionals, exception handling, and structured programming — all while solving a real-life problem.

**Language:** Python 3  
**Difficulty Level:** Beginner to Intermediate  
**No external libraries required**

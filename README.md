# Grocery Inventory Management System

### Project Title
**Simple Grocery Store Inventory Manager (Console-Based)**

### Overview of the Project
This is a beginner-level Python project that implements a basic inventory management system for a small grocery store. The program allows users to add new items, update stock quantities (restock or record sales), view the current inventory with low-stock alerts, and calculate the total monetary value of all items in stock — everything through an easy text-based menu.  
All data is stored in memory using a Python dictionary (no files or database needed).

Great for practicing dictionaries, functions, loops, input validation, and menu-driven programs.

### Features
- Add new grocery items with price and initial quantity
- Update stock (positive = add stock, negative = sell/remove) with protection against negative quantities
- Display full inventory (sorted alphabetically) with low-stock warning for items below 10 units
- Calculate and display total inventory value in dollars
- Simple, clean menu with basic input validation

### Technologies/Tools Used
- **Language:** Python 3.x
- **Libraries:** Only built-in Python standard library (zero external dependencies)

### Steps to Install & Run the Project
1. Ensure Python 3 is installed  
   (Check with `python --version` or `python3 --version`)
2. Save the code as `inventory.py`
3. Open a terminal/command prompt and navigate to the folder containing the file
4. Run the program:
   ```bash
### Instructions for testing
Add Item → Option 1 → Try adding "Apples", price 1.99, quantity 30 → Check it appears in inventory
Update Stock → Option 2 → Select "Bread" → Add 15 → Remove 10 → Try removing 100 (should be blocked)
View Inventory → Option 3 → Verify items are sorted and low-stock items show "LOW"
Total Value → Option 4 → Confirm the calculated amount matches manual calculation
Exit → Option 5 → Program should close cleanly

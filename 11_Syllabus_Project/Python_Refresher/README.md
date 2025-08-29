# Personal Expense Tracker

A simple, interactive Python project to help you track your personal expenses, set a monthly budget, and analyze your spending habits. This project is implemented as a Jupyter Notebook and is beginner-friendly, making it ideal for those looking to practice Python basics and file handling.

---

## Features

- **Add Expenses:** Enter details such as date, category, amount, and description for each expense.
- **View Expenses:** Display all recorded expenses in a readable format.
- **Set and Track Budget:** Set a monthly budget and compare your total expenses against it, with warnings if you exceed your limit.
- **Save & Load Expenses:** Persist your data by saving expenses to a CSV file and loading them automatically when you start.
- **Interactive Menu:** User-friendly menu to navigate all features.

---

## Table of Contents

- [Project Overview](#project-overview)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Code Structure](#code-structure)
- [Sample Usage](#sample-usage)
- [Customization Ideas](#customization-ideas)
- [License](#license)

---

## Project Overview

This notebook-based project allows you to:
- Log daily expenses with details
- Set a monthly spending limit
- Track your spending by category
- Save and reload your data for future sessions

---

## How It Works

1. **Add Expense:**
   - Input the date, category, amount, and description.
   - Each expense is stored as a dictionary in a list.
2. **View Expenses:**
   - Display all expenses with their details.
3. **Set & Track Budget:**
   - Set a monthly budget.
   - Compare total expenses to the budget and get alerts if you exceed it.
4. **Save/Load Expenses:**
   - Save all expenses to a CSV file.
   - Load expenses from the CSV file at startup.
5. **Interactive Menu:**
   - Choose actions from a menu-driven interface.

---

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook

### How to Run
1. Open the notebook `project_1_expense_tracker.ipynb` in Jupyter.
2. Run all cells in order, or use the interactive menu to operate the tracker.
3. Follow on-screen prompts to add/view expenses, set budgets, and save data.

---

## Code Structure

- **Imports:**
  - `datetime` for date handling
  - `csv` for file operations
- **Functions:**
  - `add_expense(expenses)` — Add a new expense
  - `view_expenses(expenses)` — View all expenses
  - `set_budget()` — Set a monthly budget
  - `track_expenses(expenses, budget)` — Compare expenses to budget
  - `save_expenses(expenses, filename)` — Save expenses to CSV
  - `fetch_expenses(filename)` — Load expenses from CSV
  - `mainMenu()` — Interactive menu for user actions

---

## Sample Usage

```python
# Add an expense
expenses = add_expense(expenses)

# View all expenses
view_expenses(expenses)

# Set a budget
budget = set_budget()

# Track expenses against budget
track_expenses(expenses, budget)

# Save expenses to file
save_expenses(expenses)

# Load expenses from file
expenses = fetch_expenses()
```

Or simply run the notebook and use the menu:

```python
if __name__ == "__main__":
    mainMenu()
```

---

## Customization Ideas

- Add expense categories and subcategories
- Visualize spending with charts (e.g., matplotlib)
- Add authentication for multiple users
- Export reports in different formats (Excel, PDF)
- Integrate with a database for advanced features

---

## License

This project is for educational purposes. Feel free to modify and use it for your own learning!

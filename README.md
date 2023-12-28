# Expense Tracking App

## Project Goal
The goal of this project is to create a Python app that enables users to track and categorize their monthly expenses, aiding in budgeting.

The app allows users to input their expense category and amount directly into the terminal. It then saves (appends) that expense entry to a file and reads the file to summarize the expense totals for the month. Additionally, it provides information on how much users can spend for the rest of the month to stay within budget (a custom value set by the app, e.g., $2000).

## 🎯 App Requirements
- Ask the user to add an expense (name, category, amount).
- Save expense entries to a .csv file.
- Read the file to summarize the expense totals for that month.
- Show the user how much they can spend for the rest of the month (to stay in budget).

## ✨ Bonus
- Show expenses by category.
- Provide the user with a rough estimate of how much they have left to spend per day.

## 💡 Recommended Project Structure
The final project will consist of 2 files:

1. **expense.py:** A class for creating and storing expense objects.
2. **expense_tracker.py:** The main application logic.

## ✅ Tasks
1. Create the `expense.py` class.
2. Create the `expense_tracker.py` file and write the main logic for the app.
3. Run the app to test it.

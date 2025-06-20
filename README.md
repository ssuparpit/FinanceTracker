# Personal Finance Tracker

This is an interactive Jupyter Notebook project designed to help users track their personal finances, visualize spending patterns, forecast future expenses, and optimize savings goals.

# Project Overview
The *FinanceTracker.ipynb* notebook loads transaction data from a CSV file into a SQLite database, provides an interactive interface to add new transactions, and generates visualizations and forecasts using Python libraries. It was developed as a personal project to demonstrate skills in data analysis, machine learning, and interactive development.

# Features
- Add Transactions: Interactive form to input new transactions (date, description, amount, type, category, account).
- Spending Visualization: Bar chart showing total spending by category.
- Monthly Trends: Line chart displaying monthly spending trends.
- Expense Forecasting: 30-day expense prediction using linear regression.
- Savings Optimization: Recommends budget allocations to meet savings goals using optimization techniques.

# Output
- Spending by Category: A bar chart displaying total debit amounts per category (e.g., Groceries, Restaurants).
- Monthly Spending Trend: A line chart showing spending trends over months (based on 2018–2019 data).
- 30-Day Forecast: A line chart predicting expenses for the next 30 days from the last recorded date.
- Optimized Budget: A table suggesting budget allocations per category to achieve a user-defined savings goal.

# Setup Instructions
1. Clone the Repository:
https://github.com/ssuparpit/FinanceTracker.git
2. Create and Activate Environment:
conda create -n finance_tracker python=3.13
conda activate finance_tracker
3. Install Dependencies:
conda install pandas numpy scikit-learn scipy plotly ipywidgets jupyter
4. Place Data File:
- Download or copy `personal_transactions.csv` (containing sample transactions) into the project folder (`C:\Users\iamar` or the cloned directory).
5. Launch Jupyter Notebook:
Open `FinanceTracker.ipynb` and run all cells to see the dashboard.

# Tech Stack
- Programming Language: Python 3.9
- Database: SQLite
- Environment: Jupyter Notebook
- Libraries: 
- `pandas` for data handling
- `numpy` for numerical operations
- `scikit-learn` for linear regression
- `scipy` for optimization
- `plotly` for interactive visualizations
- `ipywidgets` for interactive forms

# How to Use
- Run the notebook cells in order.
- Use the interactive form to add transactions (e.g., Date: 2025-06-19, Amount: 10.50, Type: debit).
- Adjust the savings goal and budget in the optimizer to see recommended allocations.
- Charts update dynamically based on the data.

# Sample Output
- **Spending by Category**: [Image](spending_by_category.png) showing total debit amounts per category.
- **Monthly Trend**: [Image](monthly_spending_trend.png) displaying spending trends over months.
- **Forecast**: [Image](30_day_forecast.png) predicting expenses for the next 30 days.

# Future Improvements
- Add export functionality for reports.
- Implement real-time data syncing.
- Enhance forecasting with more advanced models.

# Author
- Developed by: Your Name
- GitHub: [ssuparpit](https://github.com/ssuparpit)
- Date: June 19, 2025

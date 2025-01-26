# Expense Analyzer

**Expense Analyzer** is a full-stack application to manage and track expenses. You can add and update your expenses, categorize them, and see your spending over specific date ranges or by month.

## Features

- **Add and Update Expenses**: Easily add and change your expenses by date and category.
- **Analyze by Date Range**: View your expenses for a selected time period.
- **Monthly Analysis**: See how much you spend each month and track trends.

## Project Structure

The project has the following folders:

- **frontend/**: Contains the code for the Streamlit app, where you interact with the tool.
- **backend/**: Contains the code for the FastAPI server, which handles the data and requests.
- **tests/**: Contains test files to check if everything is working properly.
- **requirements.txt**: Lists all the Python libraries needed to run the project.
- **README.md**: This file, which explains the project and how to use it.

## Getting Started

Follow these steps to set up the **Expense Analyzer** on your system.

### Prerequisites

- Python 3.7 or later
- `pip` to install the required libraries

### Installation

1. **Clone the project repository:**
   ```bash
   git clone https://github.com/Jeysiva-apjs/spend-analyzer.git
   cd expense-analyzer

2. **Install dependencies:**  
   ```commandline
    pip install -r requirements.txt
   ```

3. **Run the FastAPI server:** 
   ```commandline
    cd backend
    python3 main.py
   ```
4. **Run the Streamlit app:**:   
   ```commandline
    cd frontend
    streamlit run app.py
   ```

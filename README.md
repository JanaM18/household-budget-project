# Household Budget Project

This repository contains a Python script (`database_query.py`) that connects to a PostgreSQL database named "Household Budget" and queries the `expenses` and `income` tables to display the data using pandas DataFrames. 
# Features
- Connects to a local PostgreSQL database hosted on `localhost:5432`.
- Retrieves and displays expenses and income data in tabular format.
- Uses `psycopg2` for PostgreSQL connectivity and `pandas` for data manipulation.

# Prerequisites
- **Python 3.x** (the version used during development, confirm with `python --version`).
- Installed libraries:
  - `psycopg2-binary` (install with `pip install psycopg2-binary`)
  - `pandas` (install with `pip install pandas`)
- **PostgreSQL Server** running with the "Household Budget" database.
- Database credentials:
  - Username: `postgres`
  - Password: `user_password` (note: hardcoded in the script for simplicity)
  - Host: `localhost`
  - Port: `5432`
- Git installed (version 2.49.0.windows.1 used, install from [git-scm.com](https://git-scm.com)).

 Project Setup
1. **Clone the Repository**:
   - `git clone https://github.com/naearts123/household-budget-project.git`
   - `cd household-budget-project`
2. **Install Dependencies**:
   - Run `pip install psycopg2-binary pandas` in your terminal.
3. **Configure PostgreSQL**:
   - Ensure the PostgreSQL server is running.
   - Verify the "Household Budget" database contains `expenses` and `income` tables (as seen in pgAdmin 4).
4. **Run the Script**:
   - Execute `python database_query.py` in the terminal.
   - Expected output will display "Expenses Table" and "Income Table" with data.

## How It Was Built
- Initial issues included `ModuleNotFoundError` for `psycopg2` and `pandas`, resolved by installing the libraries.
- Indentation errors were fixed, and the script was saved as `database_query.py` in `C:\Users\Users\Documents`.
- Git was installed, and the project was uploaded to GitHub with a README added manually.



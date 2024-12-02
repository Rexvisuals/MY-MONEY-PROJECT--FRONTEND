

# Income and Expense Tracker App - Backend

## Overview

This Django-based backend powers the **Income and Expense Tracker App**. It handles user authentication, income and expense data management, and API integration for the frontend.

## Features

- **User Authentication**: Login functionality.
- **Income & Expense Management**: Track and categorize income and expenses.
- **API Endpoints**: User login and upcoming features for tracking data.

## Technologies

- **Django** (Framework)
- **Django REST Framework** (APIs)
- **SQLite** (Database)
- **Python 3**

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/income-expense-tracker.git
   cd income-expense-tracker
   ```

2. **Set up the virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Run the server**:
   ```bash
   python manage.py runserver
   ```

## API Endpoints

- **POST `/accounts/login/`**: Logs in a user with `username` and `password`.

## Project Structure

- **accounts/**: User authentication.
  - `views.py`: Login logic.
  - `urls.py`: URL routing for authentication.

- **expense_tracker/**: Income and expense management (to be implemented).
  - `models.py`: Database models for income/expense.
  - `views.py`: API views for data handling.

## Development

1. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```

2. Commit changes:
   ```bash
   git commit -m "Add feature/description"
   ```

3. Push and create a pull request.

## License

MIT License

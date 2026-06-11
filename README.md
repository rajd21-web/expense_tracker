# Expense Tracker

Expense tracker in Python Flask supports the following actions:

- Login / Signup
- Add statement
- Delete statement
- Calculate final amount
- Show all statements
- Admin functionality
- Download all statements

## Run the Project

> Python 3.10.2 was used for this project.

### Create Virtual Environment

```bash
# Linux/Mac
python3 -m venv env

# Windows
python -m venv env
env\Scripts\activate
```

### Install Requirements

```bash
pip install -r requirements.txt
```

### Set Environment Variables

```bash
# Linux/Mac
export DB_URI="database_uri"
export SECRET_KEY="secret_key"

# Windows
SET DB_URI=database_uri
SET SECRET_KEY=secret_key
```

### Run

```bash
flask run
```
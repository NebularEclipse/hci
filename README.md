# HCI Project

## Description

This is a Flask-based project for the HCI (Human-Computer Interaction) course. It features a database-backed web application.

## Requirements

- Python 3.8+
- [Flask](https://flask.palletsprojects.com/)
- All dependencies listed in `requirements.txt`

## Setup Instructions

### 1. Install Dependencies

It's recommended to use a virtual environment. Then install the dependencies:

```bash
pip install -r requirements.txt
```

### 2. Initialize the Database

Run the following command to set up the database:

```bash
flask --app app init-db
```

### 3. Run the Application

Start the Flask development server in debug mode:

```bash
flask --app app run --debug
```

The app will be available at http://127.0.0.1:5000.

## Notes

* Make sure the FLASK_APP environment variable is set to app.

* Debug mode enables live reloading and detailed error messages, ideal for development.
# Bday

A Flask birthday tracker built with the CS50 Python library and SQLite.

The app lets users submit a name, month, and day, stores the entries in `birthdays.db`, and renders the saved birthday list on the home page.

## Project Structure

- `birthdays/app.py` - Flask application and routes.
- `birthdays/templates/index.html` - Main birthday form and list page.
- `birthdays/static/styles.css` - Page styling.
- `birthdays/birthdays.db` - SQLite database used by the app.

## Run Locally

```bash
cd birthdays
python -m pip install flask cs50
flask run
```

Then open the local Flask URL in your browser.

## Notes

This is a learning project based on the CS50 birthdays exercise.

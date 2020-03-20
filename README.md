# flask-tutorial
Following the official Flask tutorial [here](https://flask.palletsprojects.com/en/1.1.x/tutorial/). It is a simple blogging application with a RESTful API that allows adding/authenticating users, and CRUDing blog posts.

# Requirements
- Python 3.7
- SQLite 3

# Setup
```bash
pip install -e .
FLASK_APP=flaskr FLASK_ENV=development flask init-db
```

# Run
```bash
FLASK_APP=flaskr FLASK_ENV=development flask run
```

# Tests
Make sure you have installed `pytest` and `coverage` with `pip`. After that, just run `pytest` in the terminal to run the tests :) 

In order to check the coverage
```bash
coverage run -m pytest
coverage report
```

# flask-tutorial
Following the official Flask tutorial [here](https://flask.palletsprojects.com/en/1.1.x/tutorial/). It is a simple blogging application with a RESTful API that allows adding/authenticating users, and CRUDing blog posts.

# Requirements
- Python 3.7
- SQLite 3

# Setup
```bash
pip install -e .
```

# Run
```bash
FLASK_APP=flaskr FLASK_ENV=development flask init-db # only on the first run or when you want to clear the DB
FLASK_APP=flaskr FLASK_ENV=development flask run
```

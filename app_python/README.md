# Python app

This app is a simple Flask application that displays the current time in Moscow.
The Black formatter is used (by VS Code) to ensure that the code is formatted correctly.

## Installing

First, create a virtual environment for the project:

```
python -m venv venv
```

and activate it using the appropiate command for your OS.

The dependencies are listed in the `requirements.txt` file (using `pip freeze`) and can be installed using:

```
pip install -r requirements.txt
```

## Running

Either run the app directly from the command line:

```
python app.py
```

or using the `flask` command:

```
flask run
```

or use the provided Dockerfile:

```
docker build -t python-app .
docker run -p 5000:5000 python-app
```
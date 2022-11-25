# REST_API_101

## Description

This is a quick study i'm doing with REST API's using python 3.10.

Why to use them? Well, that was my very first question when i was starting another small project of mine. I Could actually access and consume data from a database directly in my client (front-end), but them, started to think about security and modularity.

What is it? All I could think of was about this analogy of a restaurant, costumer tables and the kitchen. Well, in my project, costumers and tables stands for users (clients), kitchen means database and server (backend)...what about the connection between them? That's where my API steps in as a waiter, noting costumer's requests to the kitchen, and then, serving them.

## Requirements

- click==8.1.3
- Flask==2.2.2
- Flask-SQLAlchemy==3.0.2
- greenlet==2.0.1
- itsdangerous==2.1.2
- Jinja2==3.1.2
- MarkupSafe==2.1.1
- SQLAlchemy==1.4.44
- Werkzeug==2.2.2

## Installation

### activate python virtual env
```bash
source .venv/bin/activate
```

### Install flask and flask-sqlalchemy
```bash
pip3 install flask
pip3 install flask-sqlalchemy
```

### Check flask 
```bash
pip show flask
```

### Start flask project (must do it everytime you open this directory)
```bash
export FLASK_APP=applications.py
export FLASK_ENV=development
flask run
```

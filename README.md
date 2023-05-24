# Newspaper Agency

## Project overview

As a chief in the newspaper agency, working with great team of Redactors, I decided to create website to track 
Newspapers, published by our agency, in a proper way.
For that purpose I decided to create a system for tracking Redactors, assigned to Newspapers.
So I will always know, who were the publishers of each Newspaper.

DB Structure:

![database structure](static/assets/img/db_structure.png)

## Installation

Create venv and install requirements
```
python -m venv venv
venv\Scripts\activate (on Windows)
source venv/bin/activate (on macOS)
pip install -r requirements.txt
```

## Usage

- To apply migrations to the database use command:
```
python manage.py migrate
```

- To run server use command:
```
python manage.py runserver
```
- To run tests use command:
```
python manage.py test
```


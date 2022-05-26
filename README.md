# Todoapp

# Introduction

This Todoapp is a platform where one can add and delete their tasks.
The person needs to register themselves by making an account.
Then they can use it for adding their tasks.

### Main features

* Adding tasks

* Deleting tasks

* Live editing of tasks.

# Usage

First clone the repository from Github.
Activate the virtualenv (if any) for your project.
    
Install project dependencies:

    $ pip install -r requirements.txt
    
    
Then simply apply the migrations:

    $ python manage.py makemigrations
    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver
You can access the default local server at http://127.0.0.1:8000/

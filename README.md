# django_trainings
This repository holds training materials for my students enrolled in backend development course.

We have two folders in this repository - one is related to Object Oriented Programming in Python, the other is related to Django.

We have the <u>Django</ul> folder as the home directory for our Django project.

Now, lets create a virtual environment for our project inside the Django folder.
```bash
# Check the python version installed
$ python --version

# Setup a virtual environment
$ python -m venv myvenv

# Activate the virtual environment
$ source myenv/bin/activate
(myvenv) $ # <-- Indicatesthe env is activated
```

A virtual environment folder will be created which contains libraries and necessary scripts for our project. We then create a file named requirements.txt to install the necessary libraries.
```Directory structure
Django
└--myvenv
   |  └ ....
   └--- requirements.txt
```

In requirements.txt file we can add Django~=5.1.2, and then run pip install -r myvenv/requirements.txt to install Django

## Creating Django project
We'll now create a skeleton structure for our Django project.
```command-line
(myvenv) $ django-admin startproject mysite .
```
This will create a folder structure needed for our django app.

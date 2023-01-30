
# Django Crud Project

## Setup

1 Download packages
```sh 
$ sudo apt install python3
$ sudo pip install pipenv
$ sudo pip3 install pipenv
```

2 Clone the repository:
```sh 
$ git clone https://github.com/cataluniat/django-crud-project
$ cd django-crud-project
```
3 Inside ./djangoproject/

```sh 
$ sudo pipenv --python /usr/bin/python3
```
*******
Command function: change version of python to use in case of not having version 3.8 that the project uses.
******* 
4 Install dependencies and start virtual enviroment
```sh
$ sudo pipenv install
$ sudo pipenv shell
```
5 Runserver
```sh 
$ cd app
$ python manage.py runserver  
```
or custom port
```sh 
$ python manage.py runserver xxxx
```
6 Exit virtual enviroment 
```sh 
$ exit
```

This project does not include a Dockerfile.

Same project with a Dockerfile:
https://github.com/Cataluniat/django-crud-docker

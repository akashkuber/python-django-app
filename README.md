# python-django-app

Download latest python

Download python IDE pycharm to code in python

set python env using following command or 
using pycharm create new project it will automatically create venv for you

$ python3 -m venv pyShop

# Activate Env
$ source pyShop/bin/activate

# check Env
$ which python

open project code in pycharm IDE and run following command

$ pip install django==2.1.5

$ django-admin startproject pyshop      // create django project

$ python3 manage,py runserver           // to run project

$ python3 manage.py startapp Products   // to create new app inside pyShop

$ python3 manage.py makemigrations      // create migration

$ python3 manage.py migrate.            // migrate the project database

$ python3 manage,py runserver           //run python project

open following into browser

http://127.0.0.1:8000/products/

login admin using following url
http://127.0.0.1:8000/admin/ 

username: demo
password: Demo@123

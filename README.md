# Default-Django-File-Structure
This is the default Django file structure



## Make directory using command
$ mkdir FILE_NAME

## Install virtualenv inside vmspm directory
$ pip install virtualenv

## Create virtualenv inside this folder
$ python -m venv env 

## Then Activate the virtualenv
##### $ .\env\Scripts\activate   -----> for Window
##### $  source env/bin/activate  ----> for Linux

## Install django and restframework 
(env) $ pip install django , (env)  $ pip install djangorestframework

## Create django project 
(env)  $ django-admin startproject project_name

## Change diectory to project_name
(env)  $ cd project_name

## MySQL database used so install mysqlclient
(env) $ project_name> pip install mysqlclient

## Then create migration file
(env) $ project_name> python manage.py makemigrations

## Then create tables in database
(env) $ project_name> python manage.py migrate

## Then create superuser
(env) $ project_name> python manage.py createsuperuser

## Runserver
(env) $ project_name> python manage.py runserver


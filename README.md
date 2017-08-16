# python_base_api
=================
# create main prject folder
1- mkdir projects && $_ 
# create virtual environment
2- virtualenv -p /usr/local/bin/python3 venv
# activate envioronment
3- source venv/bin/activate
# install django in the environment
4- pip install Django
# only if you have problems with 'pip'
(optional) if you lack pip - sudo easy_install pip
# create txt for track installations
5- touch requirements.txt
6- pip freeze > requirements.txt
# create django project
7- django-admin startproject djangorest
# install djangorestframework
8- pip install djangorestframework
# create the rest api, need be sure that you are in your active envioronmet, when you change your terminal
9- python3 manage.py startapp api
#
10-

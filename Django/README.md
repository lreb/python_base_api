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

# Test
python3 manage.py test
# Migrations
python3 manage.py makemigrations
python3 manage.py migrate


# sources
[Django Tutorial](https://docs.djangoproject.com/en/1.10/intro/tutorial01/)
[Django Rest Framework Turorial](http://www.django-rest-framework.org/tutorial/quickstart)
[Django api rest part 1](https://scotch.io/tutorials/build-a-rest-api-with-django-a-test-driven-approach-part-1)
[Django api rest part 2](https://scotch.io/tutorials/build-a-rest-api-with-django-a-test-driven-approach-part-2)

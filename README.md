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
# only iy you have problems with 'pip'
(optional) if you lack pip - sudo easy_install pip
# create txt for track installations
5- touch requirements.txt
6- pip freeze > requirements.txt
# create django project
7- django-admin startproject djangorest

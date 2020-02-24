# Hey BUDDY... this is Readme file.

######SETUP DJANGO PROJECT######

#djangodoc project explain step-by-step creating app in django documentation.

#check python version by this command  

$python3 --version

#if python3 is not install by this commant install python3  

$sudo apt-get update

$sudo apt-get install python3

#now install package manager pip

$sudo apt install python3-pip

#now create virtual environment

$sudo pip install virtualenv

$virtualenv env

$source bin/activate

#for deactivate virtual environment

$env deactivate

#create django project

$django-admin startproject mysite

#run server

$python3 manage.py runserver

#create app

$python3 manage.py startapp polls

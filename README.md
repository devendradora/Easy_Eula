Easy_Eula
=========

A new way to make the end user license agreement documents to be interactive. Built using django and introjs. 

STEPs
1) Create a Mysql database named easyeula
2) Navigate to the root of Easy_Eula folder
3) python manage.py syncdb
4) Navigate Easy_Eula\EasyEula\settings.py  and add the following details of DATABASES
    'NAME': 'easyeula',
    'USER': 'root', 
    'PASSWORD': '',
5)python manage.py runserver
6)open in your webbrowser http://127.0.0.1:8000/auth/
7) your are done !!!

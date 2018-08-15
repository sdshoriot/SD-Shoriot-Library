How to Start New Project On Python3 & Django2
=============================================
cd Desktop
mkdir boss
cd boss

virtualenv venv --python=python3.7

pip install Django==2.0.7

Python 3.7          (python --version)                        
Django 2.0.7        (python -m django --version)     
                                                           
django-admin startproject project
cd project
python manage.py makemigrations
python manage.py migrate
python manage.py runserver


How to Start Old Project On Python3 & Django2
=============================================

cd Desktop
mkdir boss
cd boss
ls

virtualenv venv --python=python3.7
source venv/bin/activate

cd project
python manage.py runserver

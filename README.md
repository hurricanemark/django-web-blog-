
# **Romiland Blog**
A web app written in python using Django framework.

# **Pre-requisites**
```
python3.7.0
Django 2.0.1
Django-crispy-forms
Pillow 2.5.0
```

# **Environment**
```
pip install --user pipenv
mkdir python-src
cd python-src
pipenv install --python 3.7
pipenv shell
pip install django
pip install django-crispy-forms
pip install Pillow
django-admin check
```

# **Configure**
Edit file settings.py

Specify hosts where the web server would be run:
`ALLOWED_HOSTS = ['192.168.100.22', 'www.myfameblog.com']`

# **Running**
python manage.py runserver localhost:9000

or 

python manage.py runserver 0:9000

or

python manage.py runserver www.myfameblog.com:9000

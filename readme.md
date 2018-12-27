## Vision
Facilitate Social Authentication via popular tech companies such as Github and Google+

# Prerequisite
- [Python3.6](https://www.python.org/downloads/release/python-365/)
- [Virtual Environment](https://virtualenv.pypa.io/en/stable/installation/)

# Installation and Setup

Clone the repository below

```
git clone git@github.com:vincentmuriuki/django-social-auth.git
git checkout develop
cd django-social-auth
cd mun
```

Ensure ```pipenv``` is installed in your system
# Install required Dependencies

```
pipenv shell
pip install -r requirements.txt
```
# Alternatively, run

```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```
# Run the application
```
python manage.py migrate
python manage.py runserver
```
Visit ```http://localhost:8000``` and signIn via Deezer, Google, and Github
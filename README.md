# Student Performance Prediction using ML

Student's Performance Prediction Web Application Using Machine Learning Approach

## Problem : Prediction of Students performance using Machine learning based on their previous data and results for early prevention.

## Steps to follow

- Install python3
  - pip install pipenv

Go to Base-Directory run following commands to start server

```bash
pipenv install
pipenv shell
python manage.py runserver
```

```bash
# migrate database for user/admin login
python manage.py migrate 
# to create admin user
python manage.py createsuperuser
```

Go to <https://localhost:8000> on your browser

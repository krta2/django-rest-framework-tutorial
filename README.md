# django-rest-framework-tutorial

## Requirements
- pip
- pyenv
- pyenv-virtualenv


## Installation
```
# Clone a repository
git clone https://github.com/krta2/django-rest-framework-tutorial.git
cd django-rest-framework-tutorial

# Create a virtualenv to isolate our package dependencies locally
pyenv virtualenv drft
pyenv activate drft

# Install requirements
pip install -r requirements.txt

# Move to project directory
cd tutorial

# Sync your database for the first time
python manage.py migrate

# Create an initial user
python manage.py createsuperuser --email admin@example.com --username admin

# Run server
python manage.py runserver
```


## Reference
- https://www.django-rest-framework.org/tutorial/1-serialization/

# Django Basic Starter Boilerplate
![Django Logo](django-logo.png)
## Using the basic django starter boilerplate
Custom User Model and management commands to create superuser and rename your project (JustDjango)

1. Clone this repo then run `git clone https://github.com/robhafemeister/Django-Basic-Boilerplate.git .`
2. Rename 'config/ex.local_settings.py' to 'config/local_settings.py'
3. `pipenv install`
4. `pipenv shell`
5. Run `python manage.py help` to see the makesuper and rename management commands in the core application.
6. To rename the project run `python manage.py rename config your_new_project_name`
7. Run `python manage.py makemigrations`
8. Run `python manage.py migrate`
9. Run `python manage.py makesuper` to create a superuser (username: admin, password: admin)
10. Change your admin password


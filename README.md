# Recipe-Django-API
This is an attempt to learn Django REST API with Test Driven Development practice on a recipe app.

# QoL Commands Here!
To generate a new project:
>This generates an app that you will be working on. It will createthe folder with
>all the necessary files in there.
    docker-compose run app --rm app sh -c "python manage.py startapp <i>appName</i>"

To run tests:
>Flake8 can be used to check for best coding practices in python programming. It can be ommitted.

    docker-compose run app sh -c "python manage.py test && flake8"

**!Important!**
>When there's a change in the models.py file, you need to run the migration command again.
<br>Migration is the instruction for Django to create the model in the real database.

    docker-compose run --rm app sh -c "python manage.py makemigrations core"

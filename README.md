# Recipe-Django-API
This is an attempt to learn Django REST API with Test Driven Development practice on a recipe app.

# QoL Commands Here!
To run tests:

    docker-compose run app sh -c "python manage.py test && flake8"


!Important
When there's a change in the models.py file, you need to run the migration command again.
Migration is the instruction for Django to create the model in the real database.

    docker-compose run app sh -c "python manage.py makemigrations core"

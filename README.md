# Personal Portfolio using Django

### Configuring Postgres
Please follow below link to correctly setup postgres database via Docker.
[Connect From Your Local Machine to a PostgreSQL Database in Docker ](https://medium.com/better-programming/connect-from-local-machine-to-postgresql-docker-container-f785f00461a7)

### Running the app

    python manage.py makemigrations
    python manage.py migrate
    python manage.py collectstatic
Now before starting the app, you need to make a super user for an admin account from which you will be able to add/update data easily via UI. Inorder to create a user, run the following command.
	
    python manage.py createsuperuser
Now you can start your application.

    python manage.py runserver

 Your app will run on port 8000 by default. --> [http://localhost:8000](http://localhost:8000/)
 And, you can access admin account here --> [http://localhost:8000/admin](http://localhost:8000/admin )

**Link to the Heroku application**

https://immense-chamber-37365.herokuapp.com/

**Running the application**

    $ python3 manage.py makemigrations
    $ python3 manage.py migrate

    $ python3 manage.py createsuperuser
    Enter username: `admin` and password: `admin12345`
    Enter username: `user1` and password: `admin12345`
    Enter username: `user2` and password: `admin12345`


**Running redis server**

    $ docker run -p 6379:6379 -d redis:2.8

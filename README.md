## Overview
This template include the laravel 10 set up, mysql, nginx as the web server, phpmyadmin as the dbms (You can use other dbms by using 127.0.0.1 and your database credentials).
This template ensure that all the development environment of each team member are same and avoid dependencies and version conflict. 

## Prerequiste
get the docker at here https://docs.docker.com/get-docker/

## Initialise
docker run --rm -v ${pwd}:/app composer install
<br>
docker-compose up
<br>
[Ctrl + C to after finish]
<br>
<b>You may need to change the database configuration in the docker-compose.yaml and .env<b>

## Open docker desktop
Click the image with the name "xxxx-app1"
<br>
Go to "Exec" tab and run the following command (All artisan command must run at here)
<br><br>

php artisan migrate --seed <br>
php artisan optimize



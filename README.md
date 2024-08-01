## Prerequiste
get the docker at here https://docs.docker.com/get-docker/

## Initialise
docker run --rm -v ${pwd}:/app composer install
<br>
docker-compose up
<br>
[Ctrl + C to after finish]

## Open docker desktop
Click the image with the name "xxxx-app1"
<br>
Go to "Exec" tab and run the following command (All artisan command must run at here)
<br><br>

php artisan migrate --seed <br>
php artisan optimize



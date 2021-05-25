# how to run 
## clone the project
    git clone url
cd to the proect folder
## install composer
    composer install
## create .env file
    cp .env.example .env
    php artisan key:generate
    php artisan config:cache
## start the server
    php artisan serve
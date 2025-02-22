# Lavalite

This is an open source of Content Management System

![Screen](https://raw.githubusercontent.com/LavaLite/docs/master/images/lavalite.png "Dashboards")

/admin
Username : superuser@lavalite.org
Password : superuser@lavalite

/user
Username : user@lavalite.org
Password : user@lavalite

/client
Username : client@lavalite.org
Password : client@lavalite

Installing Setup
php artisan lavalite:install
rename .env
php artisan key:generate
php artisan serve
http://path-to-route-folder/public


## Pretty URLs
Apache
public/.htaccess

## Accessing Configuration Values
$value = config('app.timezone');
config(['app.timezone' => 'America/Chicago']);

## Accessing The Current Application Environment
APP_ENV
$environment = App::environment();
$environment = app()->environment();


## Configuration Caching
config:cache
php artisan config:cache

## Naming Your Application
php artisan app:name Horsefly

## Maintenance Mode
resources/views/errors/503.blade.php
php artisan down
php artisan up


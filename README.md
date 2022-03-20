# tribagisto

you can install Bagisto from your console.

Execute these commands below, in order
1. composer create-project bagisto/bagisto
2. php artisan bagisto:install
To execute Bagisto:

On server:
Warning: Before going into production mode, we recommend you uninstall developer dependencies. To do that, run the command below:

composer install --no-dev

If not done, open the specified entry point in your host's file in your browser or make an entry in the host file.
On local:
php artisan serve
How to log in as admin:

http(s)://example.com/admin/login

email:admin@example.com
password:admin123


*** if some errors occour ????  *********
composer install/update
mysql server start and db create
env file edit(db connect)

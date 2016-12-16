//To run the server
php artisan serve

//To run the seeders

php artisan db:seed

//To migrate the tables in the database
php artisan migrate

//To migrate the tables in the database and update the seeders at the same time
php artisan migrate:refresh --seed

//To create new seeder
php artisan make:seeder UsersTableSeeder

//To create new migraton table
php artisan make:migration create_users_table

//To create new module and migration with one command
php artisan make:model User -m

//To create new seeder
php artisan make:seeder UsersTableSeeder

//To create new controller
php artisan make:controller PhotoController

//To clear routes
php artisan route:clear

//To clear cache files
php artisan cache:clear

// To dump everything and reload it (simply a refresh)
composer dump-autoload

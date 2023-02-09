First of all we create a project and make database with databaseName.
And then we install passport run the command:

composer require laravel/passport

And install Passport

php artisan migrate

php artisan passport:install

Install Spatie package in laravel 

 composer require spatie/laravel-permission

Use it in the app.php in config file

 'providers' => [
    // ...
    Spatie\Permission\PermissionServiceProvider::class,
];

Public migration 

php artisan vendor:publish --provider="Spatie\Permission\PermissionServiceProvider"

Clear chache in laravel 

 php artisan optimize:clear


  php artisan migrate
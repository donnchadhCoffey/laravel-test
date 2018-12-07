# laravel-test
Example Laravel project with Auth, CRUD etc.

# Process of Installation
- Repo clone here:
```
git clone https://github.com/donnchadhCoffey/laravel-test.git
```
- Create a new database, I used MySQL (bit of hassle here with php versioning later on - got it sorted in the end) 
- Copy contents out of ```.env.example``` into a new ```.env``` file (.env) - make sure databases are changed - I tried to be a little inventive (*cough* "vrtest")
-  Install composer dependencies from the handy json
```
composer install or update
```
- then generate the key and 
```
php artisan key:generate
php artisan migrate
```
- Launch web server
```
php artisan serve
```

# Laravel out of the box credits
- Laravel PHP Framework - https://laravel.com/docs/5.3/installation
- Bootstrap Framework - http://getbootstrap.com/
- jQuery Library - https://jquery.com/
- Font Awesome - http://fontawesome.io/

# License
This library is under MIT license, please look at the `LICENSE` file

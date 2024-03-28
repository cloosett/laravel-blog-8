
## Requirements
•	PHP 7.3 or higher <br>
•	Node 12.13.0 or higher <br>


```
git clone https://github.com/cloosett/laravel-blog-8/
cd laravel-blog-8
cp .env.example .env
composer install
php artisan key:generate
php artisan cache:clear && php artisan config:clear
php artisan serve
```

Create a database <br>
```
mysql
create database laravelblog;
exit;
```


```
php artisan migrate
```


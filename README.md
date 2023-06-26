# Tiktok Clone API (tiktok-clone-api)


### For this Tiktok Clone API to work you'll need the Frontend:

Tiktok Clone: https://github.com/John-Weeks-Dev/tiktok-clone

## App Setup

```
git clone https://github.com/John-Weeks-Dev/tiktok-clone-api.git
```

Then
```
composer install 

cp .env.example .env 

php artisan cache:clear 

composer dump-autoload 

php artisan key:generate

composer require laravel/breeze --dev

php artisan breeze:install (FOR THIS SELECT THE API INSTALL)

php artisan serve
```

Create a DATABASE. Make sure the DB_DATABASE in the .env is the same and then run this command 
```
php artisan migrate
```

You should be good to go!



# LaraGigs app


![Alt text](/public/images/screen.png "LaraGigs")composer update
## Setup
copy .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan storage:link
php artisan serve

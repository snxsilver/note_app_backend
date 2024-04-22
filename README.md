## About Note App Backend

Note App Backend is App Backend designed by me using Laravel 9 for fulfilling the requirements of applying a job at PT Tiga Serangkai Pustaka Mandiri.

How to install:
1. Clone the repository
2. Run composer install
3. Create table in database mysql
4. Run cp .env.example .env
5. Setting .env with suitable database
6. Run php artisan key:generate
7. Run php artisan migrate
8. Run php artisan db:seed --class=UserSeeder
9. Enjoy the app
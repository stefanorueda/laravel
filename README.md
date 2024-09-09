1. Clone the repository
2. Make sure mysql is running
3. cd to the repository
4. composer install
5. Copy the example environment file to create a new .env file (cp .env.example .env)
6. php artisan key:generate
7. Edit the .env file to set up your database connection. Update the following fields according to your local database settings:
8. php artisan migrate
9. php artisan serve

# Job Finder
Job Finder project is made in PHP using Laravel framework.

# Installation

#### 1. Clone the repository 

#### 2. Set the basic config
Edit example.env to .env <br />
Put your db username and password here with DB_DATABASE=jobportal <br />

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=jobportal
    DB_USERNAME=root
    DB_PASSWORD=

#### 3. Install Dependencies
    composer install
    npm install
    npm run dev                

#### 4. Migrate Database
    php artisan migrate:fresh
    php artisan db:seed

#### 5. Serve application
    php artisan serve

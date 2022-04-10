# Job Finder
    This project is made in PHP using Laravel framework.

# Features
    1. Two Users: Company, User
    2. Company:
        -Add job request
        -Edit request
        -Delete request
        -Company profile editing
        -Review applicants / profile
        -Recruit user for job
    3.User:
        -Apply for job
        -User profile editing
        -Editing professional details
        -View companies profile

# Installation
    1. Clone the repository

    2. Set the basic config
       Edit example.env to .env
       Put your db username and password here with 
        DB_DATABASE=jobportal
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1 
        DB_PORT=3306
        DB_DATABASE=jobportal 
        DB_USERNAME=root
        DB_PASSWORD=

    3. Install Dependencies
        ~composer install
        ~npm install
        ~npm run dev

    4. Migrate Database
        ~php artisan migrate:fresh
        ~php artisan db:seed

    5. Start Website
        ~php artisan serve

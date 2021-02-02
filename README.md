## Code Academy final project / QuizApp

 - Created by: ##Martin Nikolov
 

## Project installation steps

1. Clone the repo to your local pc

2. cd into your project

3. Inastall Composer Dependencies
    - composer install

4. Install NPM Dependencies
    - npm install && npm run dev

5. Create a copy of your .env file
    - cp .env.example .env

6. Generate an app encryption key
    - php artisan key:generate

7. Create an empty database for our application

8. In the .env file, add database information to allow Laravel to connect to the database

9. Migrate the database
    - php artisan migrate
    
10. In order to create admin
    - php artisan db:seed 
    * admin credentials: 
        - email: admin@test.com
        - pass: secret

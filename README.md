# coding_backend_test
- Go to Git Bash or your preferred text editor's terminal and run `git clone https://github.com/johnadan/coding_backend_test`
- Go to project's root directory and run `composer install` 
- Go to localhost/phpmyadmin/index.php in your browser and create a new MySQL database named `backend_coding_test`
- Copy the `.env.example` file to a new file called `.env` by running `cp .env.example .env` in the project root's directory
- Fill out the corresponding database values in the `.env` file
- Run `php artisan key:generate` in the project's root directory
- Run `php artisan migrate` in the project's root directory
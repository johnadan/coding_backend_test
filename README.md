# coding_backend_test
- Go to Git Bash or your preferred text editor's terminal and run `git clone https://github.com/johnadan/coding_backend_test`
- Go to project's root directory and run `composer install` 
- Go to localhost/phpmyadmin/index.php in your browser and create a new MySQL database named `backend_coding_test`
- Copy the `.env.example` file to a new file called `.env` by running `cp .env.example .env` in the project root's directory
- Fill out the corresponding database values in the `.env` file
- Run `php artisan key:generate` in the project's root directory
- Run `php artisan migrate` in the project's root directory
# extra
- Say for example, we need a feature where we can display featured products. How would you go about implementing this feature? (You don't need to write code for this, just describe how would you implement it)
I would add a column probably named "isFeatured" with a boolean value where if it set to true, product will be included in featured products and if false, product will be excluded in featured products. For this feature, we can set up a back-office management for admin to choose which products to include in featured products.
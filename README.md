# dottheory-d9m-challenge
Starter files for the dotTheory Drupal Module Development training track

## Running the web server
1. Go to the root of the repository.
2. Execute this command to run the PHP web server:
    ```sh
    php -S localhost:8888 -t web
    ```
3. Your site should be accessible on http://localhost:8888

## Installation
1. Go to the root of the repository.
2. Install Composer dependencies:
    ```sh
    composer install
    ```
3. Go to http://localhost:8888/core/install.php
4. On the Choose Language screen, select English and press the Save and Continue button.
5. On the Select an installation profile screen, select Standard and the press Save and Continue button.
6. On the Database configuration screen, select SQLite and press the Save and Continue button.
7. On the Configure site screen, fill the form anyway you want and press the Save and Continue button.
8. Your Drupal site should be up and running.
9. Push all the changes on your local repo.

## Exercise
- Create a custom module named Sandbox
- Create a form accessible on /admin/config/system/featured
  - Add a field named Featured Youtube ID
  - Add the link of the Form on /admin/config, under the System panel
- Create a page accessible on /featured
  - Render the embedded Youtube video on the page based on the value entered on the Featured form
  - Apply cache tags invalidator 

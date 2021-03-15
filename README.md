# ORM eCommerce Back End

## Description:

This ORM eCommerce Back End application is to aid companies in building an eCommerce database.  The application takes a working Express.js API and configures it to use Sequelize to interact with a MySQL database.

ORM eCommerce Back End does the following:
1. Uses an environment-variable file to store authentication information used to connect to the MySQL database using Sequelize.
2. Uses schema and seed files to create the database then seeds it with test data.
3. Uses Insomnia Core to test database activities.
4. Uses the API GET routes to retrieve database data for categories, products, or tags
5. Uses the API POST routes to add new datat to the database.
6. Uses the PUT routes to update data in the database.
7. Uses the DELETE routes to delete data from the database.

## How to clone this Employee Tracker:

1. In your browser, navigate to the (https://github.com/shellienguyen/orm-ecommerce-backend) GitHub repository.
2. Click the green button that says “Code” and copy the SSH key to your clipboard.
3) Navigate to your terminal and to the working directory where you want this repository to be housed at.
4. At the terminal command line, type “git clone ” and paste the SSH key you copied from the repository, hit Enter.
5. This application uses Node.js, Sequelize, and MySQL. Due to large file size these dependencies will not be cloned to your repository.
You will need to install dependencies before executing the application.
6. Open the project in Visul Studio Code and open the "Integrated Terminal.  At the integrated command line inside Visual Studio
Code, type in "npm install" to install the node modules.
7. Then at the command line, type in "npm express sequelize mysql2" to install the other dependencies dependencies.
8. Creat a ".env" file at the root directory with the following variables (NOTE: you must replace the info in the brackets with your MySQL username and password and remove the brackets):
    - DB_USER={Your MySQL username}
    - DB_PD={Your MySQL Password}
    - DB_NAME=ecommerce_db

## Instuctional Video:

For a demonstration on how to run this application, please watch this video: 

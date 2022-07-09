# E-commerce

Authored by Charissa Hollister 07/09/2022

## Description

E-Commerce is a database application that can be used to track, add, and update your store inventory database. ecommerce_db database contains tables to track and manage Products, Categories, and Tags, as well as their associated information. _npm start_ can get the inventory organized and ready for success.

## Instructions

On initial set up it will be required that the user enters their specific mysql login information and reference to the ecommerce_db database in their .env file, install the npm packages, and run the mysql file schema.sql to create a clean database.  
Once the database is present on the local computer all that is needed to begin the application is a REST Client and to enter _npm start_  
Users can continue to track, add, delete and update for as many loops as is necessary.  
Entering Ctrl-C in the command-line will stop the server and exit the program.  

note: there are seeds available with test data by entering _npm run seed_  

## Demo

### Demo online link
https://drive.google.com/file/d/1DA3bupewWYJUA7hC6eFsApI2P0_WxjNF/view

### GitHub Repo:
https://github.com/CharissaHollister/E-Commerce

### Minimum customer criteria

AS A manager at an internet retail company  
I WANT a back end for my e-commerce website that uses the latest technologies  
SO THAT my company can compete with other e-commerce companies

GIVEN a functional Express.js API  
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file  
THEN I am able to connect to a database using Sequelize  
WHEN I enter schema and seed commands  
THEN a development database is created and is seeded with test data  
WHEN I enter the command to invoke the application  
THEN my server is started and the Sequelize models are synced to the MySQL database  
WHEN I open API GET routes in Insomnia for categories, products, or tags  
THEN the data for each of these routes is displayed in a formatted JSON  
WHEN I test API POST, PUT, and DELETE routes in Insomnia  
THEN I am able to successfully create, update, and delete data in my database

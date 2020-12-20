# E-commerce Back End

   ![Language](https://img.shields.io/badge/Lang-JavaScript-yellow)

  ## Table of Contents
  1. [Description](#description)
  2. [Installation Instructions](#installation-instructions)
  3. [Usage Information](#usage-information)
  4. [Tests](#tests)
  5. [Questions](#questions)
 
  
  ## Description
  Using the Sequelize ORM, create models and routes for the RESTful api end-points for an already functional Express.js API.

  When the schema and seed commands are entered, the development database is created in MYSQL and is seeded with test data.  Then invoke the the application and test the end-points in Insomnia core including CRUD routes for:
  Category, Product and Tag, as well as showing one of those items by ID.

  [Github Pages](https://github.com/webprinc3ss/e-commerce-back-end)

  [Link to Demo](https://drive.google.com/file/d/150fot3lkTtuUIntXz6A6Bh_7sP0vW6gg/view)

  ## Installation Instructions

[Clone the repo](git@github.com:webprinc3ss/e-commerce-back-end.git)

[Install node.js](https://nodejs.org/en/)

[Install npm, Express, Sequelize, MySql, dotenv](https://www.npmjs.com/)
    
    npm install express sequelize mysql2

[Create: a dotenv file to hide your password](https://www.npmjs.com/package/dotenv)

[Install console.table](https://www.npmjs.com/package/console.table)
   
  ## Usage Information
    Run the following commands in your VCS integrated terminal 
        
    1.  To create the database:
            mysql -u root -p
            source db/schema.sql
            show databases;
            quit;
        
    2.  Seed the database
            npm run seed

    3.  Run the app
            npm run start
            or
            node server

  ## Tests
  Use Insomnia Core to test the following endpoints
  [Download Insomnia Core](https://insomnia.rest/download/core/)

    Tags
        GET:        http://localhost:3001/api/tags
        GET by ID:  http://localhost:3001/api/tags/1
        CREATE:     http://localhost:3001/api/tags
        UPDATE:     http://localhost:3001/api/tags/1
        DELETE:     http://localhost:3001/api/tags/1

    Products
        GET:        http://localhost:3001/api/products
        GET by ID:  http://localhost:3001/api/products/1
        CREATE:     http://localhost:3001/api/products
        UPDATE:     http://localhost:3001/api/products/1
        DELETE:     http://localhost:3001/api/products/1

    Categories
        GET:        http://localhost:3001/api/categories
        GET by ID:  http://localhost:3001/api/categorie/1
        CREATE:     http://localhost:3001/api/categories
        UPDATE:     http://localhost:3001/api/categorie/1
        DELETE:     http://localhost:3001/api/categorie/1

  ## Questions
  Please feel free to contact me, webprinc3ss at Github: https://github.com/webprinc3ss 

  or

  djabranton@gmail.com. 
      
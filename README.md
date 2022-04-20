# E-commerce Back End

# Purpose
Create the back-end for an e-commerce website that uses the latest technologies.

# Acceptance Criteria
GIVEN a functional Express.js API <br/>
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file <br/>
THEN I am able to connect to a database using Sequelize <br/>
WHEN I enter schema and seed commands <br/>
THEN a development database is created and is seeded with test data <br/>
WHEN I enter the command to invoke the application <br/>
THEN my server is started and the Sequelize models are synced to the MySQL database <br/>
WHEN I open API GET routes in Insomnia for categories, products, or tags <br/>
THEN the data for each of these routes is displayed in a formatted JSON <br/>
WHEN I test API POST, PUT, and DELETE routes in Insomnia <br/>
THEN I am able to successfully create, update, and delete data in my database

# Screenshots

# Installation
1. Clone the repo
2. create  .env file with your database name, and your mysql username and password in the following format
```
DB_NAME=ecommerce_db
DB_USER= <username>
DB_PW= <password>
```
3. type "npm i" in your desired terminal
4. log in to mysql in the terminal and type "source db/schema.sql"
5. "quit" the mysql 
6. type "node seeds/index.js"
7. "npm start" 
8. navigate to insomnia or wherever you'd like to test out the routes!

# Made With
- dotenv
- Express.js
- Node
- MySQL
- Sequelize

# Link to Video
[!]


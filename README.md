
# ORM Challenge: E-Commerce Back End

This application is an Express.js API that connects to a MySQL database using Sequelize. User can test the API's GET, POST, PUT, and DELETE routes using Insomnia Core to display or modify the data stored in the database.


## 🚀 Description

- With a functional Express.js API, the database name, MySQL username, and MySQL password were added to an environment variable file, allowing for the connection to the database using Sequelize. 
- When Schema and seed commands were entered, it creating a development database and seeding it with test data. 
- When the command to invoke the application was executed, it starting the server and syncing the Sequelize models to the MySQL database. 
- When the API GET routes were opened in Insomnia Core for categories, products, or tags, displaying the data for each of these routes in a formatted JSON. 
- When the API POST, PUT, and DELETE routes were tested in Insomnia Core, successfully creating, updating, and deleting data in the database.

## 📺 Demo


[Click here for walk through video](https://user-images.githubusercontent.com/112605297/216190534-db430953-caf9-417e-882d-46c27fcf1e0d.mp4)
## 🛠 Technologies 

**Runtime:** Node.js

**Lanuage:** Javascript

**Dependencies:** 

    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "mysql2": "^2.1.0",
    "sequelize": "^5.21.7"


## 💾 Installation


With the package.json file, use jest to excute the tests in the terminal by the following command:
```
npm i
```

Or install all the following dependencices:
```
npm instal express

npm install mysql2

npm install sequelize

npm install dotenv
```
For npm scripts:
```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node server.js",
    "watch": "nodemon server.js",
    "seed": "node seeds/index.js"
  }
```
## Usage

To excute MySQL shell in the terminal by the following command:
```
mysql -u root
```
or if you have a password for database try:
```
mysql -u root -p
```
then source the schema file:
```
SOURCE db/schema.sql;
```
To seed the database:
```
npm run seed
```
To start the server:
```
npm start
```


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)


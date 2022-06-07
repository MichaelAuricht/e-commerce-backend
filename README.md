# e-commerce-backend

## Description

This is a REST API for an internet retail website using Express.js, Sequelize and MySQL.

### Functionality

This app is capable of creating, viewing and updating categories, products & tags.

It can also delete entries from the database and establish associations between the different entities.

### Installation & Usage Instructions

Start with cloning this repo on your local machine:

```sh
$ git clone https://github.com/lukecp5/e-commerce-backend.git
$ cd e-commerce-backend
```

To install and set up the application, run:
```sh
$ npm install employee-tracker
```

You will also need to place a .env file in the root directory of the project, in order to connect to your MySQL database. Here's an example:

file: .env
```
DB_NAME=library_db
DB_PASSWORD=
DB_USER=root
```

To finish the set-up the application, complete the following steps:
1. Create a MySQL database on your local machine using the *schema.sql* file located in the /db/ directory(From the MySQL CLI, source db/schema.sql)
2. Seed the database with sample data to be used for testing purposes(Run *npm run seed* from inside the root directory of the project)

Now you're ready to start the application! You can start the server by running: 
```
npm start
```

The server is running, now you can make requests to it through your desired method.

---

### Technologies Used

Node, Sequelize, Express, MySQL

## Screenshot

## Video Link

GitBash Input - https://drive.google.com/file/d/1yEEaCvQebNDg8-miz8kOabD-JTmCaZlh/view?usp=sharing

Insomnia Display - 
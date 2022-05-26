# (ORM): E-Commerce Back End (SJB-ORM-E-Commerce)

##  Description

This application is...


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Preview 

###### Create Database, Seed data and start the application’s server

<!-- ![exampleOfUsingEmployeeTracker](./assets/employee-tracker-overview.gif) -->

###### Example of adding employee



###### Example of updating employee's roll and manager. Deleting employee



## Installation 

###### Local Installation
* Clone the repository from [Github](git@github.com:simmmmo/SJB-ORM-E-Commerce.git)
* Ensure Node.js is installed
* Ensure MySQL is installed
* Install dependencies 
[express package](https://www.npmjs.com/package/express)
```bash
npm i
```
```bash
npm i sequelize
```
```bash
npm i mysql2
```
```bash
npm i dotenv
```

* Create .env file in the root directory and add local SQL credentials
```bash
DB_USER='YourUser'
DB_PW='YourPW'
DB_NAME='ecommerce_db'
```
* Log into MySQL and import DB schema file

```bash
mysql -u root -p

source db/schema.sql

```
* Run Seed once the database has be created to populate seed data to your database

```bash

npm run seed

```


## Usage 

###### Local Environment 
Run 
```bash
npm start
```

Open Insomnia App 



###### Addition information
* Note - Before starting application, ensure MySQL credentials have been updated 


## Technology 
* Node.js
* Express.js
* MySQL
* sequelize


## Project Links

###### Walkthrough video links
Create the schema, seed the database and start the application’s server



GET routes for all categories, all products, and all tags being tested in Insomnia.



GET routes for a single category, a single product, and a single tag being tested in Insomnia.



POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia.




###### Repo name

* SJB-ORM-E-Commerce

###### GitHub enviroment

* https://github.com/simmmmo/SJB-ORM-E-Commerce
* git@github.com:simmmmo/SJB-ORM-E-Commerce.git

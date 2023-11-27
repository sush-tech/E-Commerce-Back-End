# E-Commerce-Backend
The challenge is to build the back end for an e-commerce site.

## Table Of Content
* [General Info](#general-info)
* [Installation](#installation)
* [Usage](#usage)
* [References](#References)

## General Info
We’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database. This application won’t be deployed so i’ll show a walkthrough video that demonstrates its functionality.<br>
Application running in Insomnia
https://drive.google.com/file/d/1ousUw8FRs3Q-KdfqgV7KH5QhIJqr-JhX/view

Demonstration Video
https://drive.google.com/file/d/1bYlIAO0Q8Wi_3WNKsaLPrnOPgQLbpXPv/view

## Installation
To get started clone this repository using 
<br>
```terminal
git clone git@github.com:BennAsabir/employee-tracker.git
```
Both Node.js and MySQL must be installed on your computer.

Install dependencies 
```terminal
npm init --y
``` 
```terminal
npm install express sequelize mysql2
```
Open up MySQL shell and input 
```terminal
source db/schema.sql
```
and 
```terminal
use ecommerce_db
```
Then quit MySQL shell and input the following in your terminal
```terminal
npm run seed
```
to start running application simply input 
```terminal
node server.js
```
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage
The application is used to GET, create, update, and delete data in these routes(categories, products, or tags).


## References
https://github.com/BennAsabir/e-commerce-backend
https://github.com/Bwogi/e-commerce-backend
https://github.com/umairkhalid/ORM-E-commerce-back-end

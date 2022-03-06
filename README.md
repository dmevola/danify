# Danify

Danify is a backend CMS system for an ecommerce website. It was built using MySQL2, Express.js, node.js, Sequelize, and dotenv.

## Installation

To install danify:

- npm init
- npm install mysql2
- npm install sequelize
- npm install dotenv

Initial run
- mysql -u root -p
- Set up the schema with source db/schema.sql
- Quit mysql
- Seed by running npm run seed
- npm start to run the server

## What does it do?
Danify allows for creating, reading, updating, and deleting products, categories, and tags which are related in the SQL database. Custom routes have been created to allow for performing GETs, POSTs, PUTs, and DELETEs for categories, tags, and products. 

## Demo
To watch a live demo of this functionality, see links below
- [Part 1](https://drive.google.com/file/d/1Az5v7rBmBM4_2YwyhzXm20CLkoPG-mjv/view)
- [Part 2](https://drive.google.com/file/d/1Cm_iT75NTK7_U_X0OFp1Ej4xIoCXhPB7/view)

## Contact

Danify was made by [Dan Evola](https://dmevola.github.io/portfolio)
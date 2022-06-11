# E-commerce-Back-End
# Gihub Repository
https://github.com/Pablogarciag02/E-commerce-Back-End
## Video link
[Youtube Video showing how it works](https://note-taker-pablogarciag02.herokuapp.com/)
## About this Project
-Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence

-Due to this, With starter code, i made a database with Sequelize that contains all the categories, products and tags for an online retailer, also known as e-commerce

-This in turn makes it easy for a company to take note of every purchase, every item that goes inside of different categories.

This project uses
[Express](https://www.npmjs.com/package/express) server Web Framework
[dotenv](https://www.npmjs.com/package/dotenv) server Web Framework
[mysql2](https://www.npmjs.com/package/mysql2) server Web Framework
[sequelize](https://www.npmjs.com/package/sequelize) server Web Framework



![Example](/Assets/Example.jpg)
![Example2](/Assets/Example2.jpg)
Create an ecomerce database using sequelize and manipulate it using mysql2 and CRUD routes with express

## Table of Contents
-Installation
-Credits
-Licence
-Features
-Contribution


### Installation
*Step 1*: Install all dependencies by writing the following in the command terminal `npm i ` This will install dotenv, express, mysql2 and sequelize.

*Step 2*: Go [here](/Develop/db/schema.sql) And copy the command. 

*Step 3*: Open SQL and create a new DATABASE with the command you copied in step 2.

*Step 4*: Once database has been created, open the following file [/Develop/seeds/index.js](/Develop/seeds/index.js). Open this file in the integrated terminal, and run it by typing `node index.js` This will then populate your database with information.

*Step 5*: Run `node server.js`in the integrated terminal.

*Step 6*: This will start the local server. 

*Step 7*: in insomnia look for localhost:3001/api/`products`, `categories` or `tags` and add the information you want.




### Credits
Pablo Eugenio Garcia
Github: [Pablogarciag02](https://github.com/Pablogarciag02)
LinkedIn: [Pablo-Eugenio-Gacía](https://www.linkedin.com/in/pablo-garc%C3%ADa-08842621b/)

## Licence
MIT License

Copyright (c) 2022 Pablo Eugenio Garcia

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Features
Allows the user to create, manipulate and manage an ecommerce DATABASE using SQL, sequelize, mysql2 and express

## Contribution
Feel free to fork and use this project for your personal use if you are a business owner, or a busy student. Or if you want to make it better you can ask for a pull request 
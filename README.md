# Nursing Home Stock Management System

![Maquillaje El Roble](https://i.ibb.co/5xWjYfg/mackup-elroble-min.webp)


![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

This project is a stock management system specifically designed for a nursing home, which allows for tracking the products used in various areas of the home, such as the kitchen, nursing station, maintenance, and more.

The system has been developed using PHP as the programming language, Bulma as the CSS framework, and PHPMyAdmin as the database management tool. It is a web application that can be run on any web server that supports PHP.

## Features

The main features of the system include:

- Product management: allows for registering the various products used in the nursing home, indicating their name, description, category, unit of measure, and quantity available in stock.
- Supplier management: allows for registering the various suppliers of the products, indicating their name, address, email, and contact phone number.
- Order management: allows for placing orders for products with registered suppliers, indicating the products requested, the quantity required, and the estimated delivery date.
- Stock in/out management: allows for tracking the inflow and outflow of products from the stock, indicating the date, product, quantity, and area of the nursing home that used the product.
- Reporting and statistics: allows for generating reports and statistics on the most used products, most frequent suppliers, areas that consume the most products, and more.

## Installation

To install the system on your server, follow these steps:

1. Clone the repository on your web server:

```sh
git clone https://github.com/mcfigue/nhs.git
```
Create a database in PHPMyAdmin with the desired name and execute the database.sql script located in the database folder to create the necessary tables in the database.
Open the config.php file located in the root of the project and modify the values of the $dbHost, $dbName, $dbUser, and $dbPassword variables according to your server configuration and the database created in step 2.
Start the web server and open the browser at the corresponding URL.

Updates
This project is constantly evolving, and new features and improvements will be added over time. To keep the system up to date, follow these steps:

Download the latest version of the repository on your web server:

```
git pull origin master
```
Execute the database-update.sql script located in the database folder to update the database structure if necessary.
Check for changes in the config.php file and make the corresponding modifications if necessary.
Restart the web server and check that the system is running correctly.

Conclusion
This stock management system for a nursing home is a very useful tool for efficiently tracking the products used in the home, reducing waste and ensuring that the necessary supplies are always available.```

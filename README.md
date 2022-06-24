### fictional-fiesta

### Module 13 challenge

# E-Commerce Back End

## Description

This application was designed as a part of module 13 orm challenge. For this challenge we are supposed to design a server that will work as a back-end for an e-commerce website.

This challenge emphasizes the use of ORM and sequelize. Models are used to create classes and relationships are established between them. Routes are establised for proper functioning.

For this challenge three models are created: Category, Product and Tag. And the relationships are established in a way that a product belongs to a category, a category has many products, a product has many tags and a tag has many products.

The user can make get, post, put and delete request for any product, category and tag.

Some sample data has been used to demonstrate this application. This data is not real.


## Table of contents

[Installation](#installation)

[Usage](#usage)

[Links](#links)


## Installation

After cloning the repository, run command "npm install" to install all the dependencies for the application.


## Usage

To use this application, change the user_name, password for mysql and a database of your choice in .env file. Then run "npm start" command. 

You'll need to use Insomnia software to make HTTP request.

Please watch the walk through video for further guidance.


## Links

[GitHub Repository](https://github.com/Pooja3093/fictional-fiesta.git)

[Walk Through Video](https://drive.google.com/file/d/19mSCgFR-7pmhKS0wZPx471MDKfr579IU/view)
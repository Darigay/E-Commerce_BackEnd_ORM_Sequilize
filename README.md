# E-Commerce_BackEnd_ORM_Sequilize

## GitHub 
The URL of the GitHub repository
https://github.com/Darigay/E-Commerce_BackEnd_ORM_Sequilize

## Table of Contents
- Description
- usage
- Technologies
- Dependencies
- Screenshots
- Resources
- Contact

## Description:
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes.

The application is to build the back end for an e-commerce site. The application takes a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Usage
In the functional Express.js API when we add user database name, MySQL username, and MySQL password to an environment variable file
then we are able to connect to a database using Sequelize, when we run the schema and seed commands.
After the commands development database is created and is seeded with test data.
Then the user enter the "node server.js" to invoke the application, by which server is started and the Sequelize models are synced to the MySQL database.
User upon opening API GET routes in Insomnia for categories, products, or tags the data for each of these routes is displayed in a formatted JSON.
Similarly, user can test API POST, PUT, and DELETE routes in Insomnia,  user is able to successfully create, update, and delete data in my database.

## WalkThrough Video
the video explains the dependencies, Run , seed the application along with interaction with database using Insomnia

https://user-images.githubusercontent.com/94805706/159204230-2e72410b-e208-4dad-8d92-01e0f61459c8.mp4


## Technologies
- Javascript
- Node.Js
- mysql2
- npm packages 
- Github

## Dependencies
- CLI
- MySQL2
- Sequilize
- dotenv package
- Express.js

## Screenshots
- GetAllCategories
![GetAllCategories](https://user-images.githubusercontent.com/94805706/159201554-2e4a4301-ed7d-4eec-b72d-e8e53dc19171.png)
- Post New Product
![PostNewProduct](https://user-images.githubusercontent.com/94805706/159201565-c3bbbe52-a07b-4426-be2d-4d87818ddb74.png)
- Update A Tag
![UpdateTag](https://user-images.githubusercontent.com/94805706/159201572-4fa7f8f3-a1d2-45cc-8f28-607377010aec.png)
- Delete a Tag
![DeleteTag](https://user-images.githubusercontent.com/94805706/159201576-a6e86718-3c97-406a-9540-39b17de93035.png)


## Resources
- UofU BootCamp Object-Relational Mapping (ORM) Modules
- Sequilize Documentation

## Contact
Email Address : divya.arigay@gmail.com 
Github: Darigay@github.com


© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.



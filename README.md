# Object-Relational Mapping (ORM) Challenge: E-commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Link to demonstration video: 

## Description 

The goal of this project was to build the back end for an e-commerce site using an Express.js API and configuring it to use Sequelize to interact with the database. It includes the implementation of API routes for products, categories, and tags. It also shows how to connect to the database, seed initial data, and sync Sequelize models for database management, and provides CRUD (create, read, update, and delete) functionality. 

## Table Of Contents 
- [Installation](#installation)<br>
- [Usage](#usage)<br>
- [License](#license)<br>
- [Credits](#credits)<br>
- [Questions](#questions)<br>

## Installation

In order to use this application, you will need to install the following programs on your computer: 

- [Visual Studio Code](https://code.visualstudio.com/) 
- [Node.js](https://nodejs.org/en) 
- [MySQL](https://dev.mysql.com/downloads/mysql/)
- [Git Bash](https://gitforwindows.org/)
- [Insomnia](https://docs.insomnia.rest/)

Once you've completed installing the above programs onto your computer, initialize the application following these steps:

1. Follow the instructions on this webpage to [clone the repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).
   
2. Next, you'll want to open GitBash and run the following commands in the terminal: 

3. "npm install" to install Node Package Manager.

4. Edit the .env file to include your MySQL username and password.   

5. Once all of the dependencies are installed, you will need to configure your MySQL database. If you haven't already, go [here](https://dev.mysql.com/downloads/mysql/) to install MySQL, and follow the directions listed [here](https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide) for help. 
   
6.  After installing MySQL, open the terminal window and run the command "mysql -u root -p" to initialize MySQL. Enter your username and password when prompted to log in. 

7.  Once you are logged in, run the command "source db/schema.sql" to create the database schema for this application, and "npm run seed" to populate the database with inital data. 

8. Finally, you will invoke the application and sync the Sequelize models to the MySQL database by running the command "npm start".   

## Usage

Now that you've installed the necessary programs and Node.js packages, as well as start the server, follow these steps to use this application: 

1. After starting the server using the command "npm start", you can then open Insomnia. 

2. Once you have opended Insomnia, you can either send a POST request to create a new product/category/tag, GET request to retrieve data, PUT request to update data, or DELETE request to remove data. 

## License 

This application is covered under the [MIT License](https://opensource.org/license/mit/).

## Credits

- My tutor, Alex Gonzalez, helped me identify the issue with my Product CREATE and UPDATE operations, which resulted in a bad request response. He pointed out that I was missing the "tagIds" key in my JSON object.
  
- I referenced this website for how to setup validations: https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/

- I referenced this website for setting default value: https://sebhastian.com/sequelize-default-value/

- I referenced this website for how to reference a model: https://sequelize.org/docs/v6/other-topics/constraints-and-circularities/#enforcing-a-foreign-key-reference-without-constraints

- I referenced this website for associations: https://sequelize.org/docs/v6/advanced-association-concepts/creating-with-associations/#belongsto--hasmany--hasone-association

- I referenced Module 13 Activity 9 for findAll method

## Questions

If you'd like to view more of my work, please visit my GitHub profile: [juliaghany](https://github.com/juliaghany)

If you have any questions about my work, you can reach me at: juliaghany@msn.com

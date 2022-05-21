# E-commerce-BackEnd ![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

_by Latravia Gordon_</br>

## Description

> > > Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites. </br> Your challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
  <!-- - [Walkthrough](#walkthrough) -->
  - [Screenshot](#screenshot)
- [Tests](#tests)
- [Questions](#questions)
- [License](#license)

# Requirements

<!-- ![User Story and Acceptance Criteria]() -->

> User Story: </br>
> AS A manager at an internet retail company
> I WANT a back end for my e-commerce website that uses the latest technologies
> SO THAT my company can compete with other e-commerce companies </br>

---

> Acceptance Criteria: </br>
> GIVEN a functional Express.js API
> WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
> THEN I am able to connect to a database using Sequelize
> WHEN I enter schema and seed commands
> THEN a development database is created and is seeded with test data
> WHEN I enter the command to invoke the application
> THEN my server is started and the Sequelize models are synced to the MySQL database
> WHEN I open API GET routes in Insomnia for categories, products, or tags
> THEN the data for each of these routes is displayed in a formatted JSON
> WHEN I test API POST, PUT, and DELETE routes in Insomnia
> THEN I am able to successfully create, update, and delete data in my database

## Installation

- To install, clone this repository then make sure to have `Node.js`,`Express,.js`, and `Sequelize` installed. </br> `MySQL` is the database used with this project and because it is password protected, make sure to create a `.env` file and install the `dotenv` dependency. </br> Use `npm run seed` to seed the database, then connect to the server by running `npm start` or `node server`.

# Usage

![ORM](/Develop/./assets/images/Insomnia.gif)

# Walkthrough

Walkthrough video can be found via [YouTube](https://youtu.be/lRZn0WGreTA).

# Screenshot

<!-- ![CreateProduct](./assets/images/createProd.jpeg) -->

![DeleteCategory](/Develop/./assets/images/deleteCat.jpeg)
![UpdateCategory](/Develop/./assets/images/updateCat.jpeg)
![UpdateTag](/Develop/./assets/images/updateTag.jpeg)

## Tests

- There are no test for this application.

## Questions

For any questions about the project, please contact me by either of the following links:

- Email = gordonlc18@gmail.com
  or visit my GitHub profile:
- GitHub - [gordonlc18](https://github.com/gordonlc18)

## License

This project is licensed under the MIT license.

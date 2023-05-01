#  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This project is a back end for an e-commmerce website built with the latest technologies using Express.js API and configured to use Sequelize to interact with a MySQL database. 

The goal of this project is to create a fully functional back end for an e-commerce site, allowing the company to compete with other e-commerce companies.

The application satifies the following user story and acceptance criteria:

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Badges](#badges)

## Installation

To run the application, the following steps should be followed:

1. Clone the repository to your local machine.
2. Navigate to the project directory using the command line.
3. Run the command "npm install" to install all necessary dependencies.
4. Create an envireonment variable file '.env' in the root directory and add a database name, MySQL username, and MySQL password to it.
5. Run 'npm run seed' to create and seed the database.
6. Run 'npm start' to start the server and sync the Sequelize models to the MySQL database.


## Usage

The project uses the following technologies:
* Express.js
* Squelize
* MySQL2
* dotenv

Link to walkthrough below:


## Credits

The original code for the Express.js API was provided by the bootcamp. The configuration to interact with a MySQL database was added by, Emmanuel Lakis (https://github.com/pexApred)

Benicio Lopez - Tutor

Video Submission guide - https://coding-boot-camp.github.io/full-stack/computer-literacy/video-submission-guide

NPM Documentation: https://www.npmjs.com/package/mysql2

## License

MIT License

Copyright (c) 2023 Emmanuel Lakis

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

## Badges

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

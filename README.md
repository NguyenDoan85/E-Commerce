<h1 align="center">E-Commerce Using MySQL, Sequalize, and Express</h1>

<p align="center">
    <img src="https://img.shields.io/github/repo-size/NguyenDoan85/E-Commerce" />
    <img src="https://img.shields.io/github/languages/top/NguyenDoan85/E-Commerce"  />
    <img src="https://img.shields.io/github/issues/NguyenDoan85/E-Commerce" />
    <img src="https://img.shields.io/github/last-commit/NguyenDoan85/E-Commerce" >
    </a>
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/Sequalize-blue"  />
    <img src="https://img.shields.io/badge/-screentogif-lightgrey" />
    <img src="https://img.shields.io/badge/dotev-orange" />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/Express-green" />
    
</p>

<p align="center">
    <img src="http://img.shields.io/badge/license-MIT-blue.svg"/>
</p>

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Description

🔍 An application that used mysql database backend for an e-commerce site.

## User Story

- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria

- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia Core for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
- THEN I am able to successfully create, update, and delete data in my database

## Installation 
- 💾Clone the repo and use command `npm install` to install all require packages. 
- 💾Edit the .evn.EXAMPLE file to your configurator, then rename it to `.evn`.

## Usage 
- Login to your `mysql` to run `source schema.sql` in db sub folder which will create an e-commerce database. Warning this will drop your current e-commerce database if you already have one.
- Then run `node index.js` in seeds subfolder to create basic database structure.
- Run the following command at the root of your project and answer the prompted questions:  
`npm start`
- Then follow the option.
- 💻 Gif showing the functionality of the app.
![Company Roster](./asset/example.gif)

## License
✏️ This project is license under MIT

## Contributing

Please refer to "Fork" or be assigned by Owner.

## Questions

If you have any questions about this project, please contact me directly at ericdoan2008@gmail.com. You can view more of my projects at https://github.com/NguyenDoan85.
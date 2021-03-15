# Tech Blog

![GitHub license](https://img.shields.io/badge/license-MIT-ff69b4.svg)

## Table of Contents 

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Deployed](#deployed)
- [Languages](#languages)
- [Screenshots](#screenshots)
- [Demo](#demo)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Description

A CMS-style blog site where developers can publish their blog posts and comment on other developers’ posts as well. This app uses Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## Installation

```
// Clone the repository to your local machine using:|

git clone git@github.com:malloryfaria/tech-blog.git

// Install all the dependencies by typing code:
npm i

// Ensure you have set up MySQL and you have a legacy password to log in with ****

// Create a .env file in the root of the folder and fill out the following with your information:
DB_NAME='tech_blog_db'
DB_USER='root'
DB_PW='examplepassword'

// From the root folder, login to your MySQL using:
mysql -u root -p

// Then, run this command to create the database:
source db/schema.sql;

// Then quit the MySQL shell by typing
quit;

// Seed the test data into the database by typing:
npm run seeds

// Then use the below command to start the server:
npm start

```

## Usage
Use this application to build on the front end for an e-commerce site to this back end.

## Deployed application link
https://github.com/malloryfaria/tech-blog

## Demo
https://youtu.be/example

## Languages/Technology Used
Node, Express.js API, Sequelize, MySQL2, Handlebars.js, Express-session, bcrypt, dotenv

## Screenshots
![example](./assets/images/screenshot.jpg?raw=true) <br /><br />

## License

  This project is licensed under the MIT license.
  
## Contributing
If you would like to contribute, please reach out to me. You can find my contact information in the  "Questions?" section below.

## Questions?

If you have any questions about the project, contact me at: mallory.faria@gmail.com
Check out the rest of my work at: [malloryfaria](https://github.com/malloryfaria/)

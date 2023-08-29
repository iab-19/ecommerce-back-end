
  <!-- Remove comments after generation as they are to be used as a guide to help get started-->
  # E-Commerce Back End

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Description
  A back end application for an e-commerce website
  ### User Story
  AS A manager at an internet retail company  
  I WANT a back end for my e-commerce website that uses the latest technologies  
  SO THAT my comany can compete with other e-commerce companies

  ### Acceptance Criteria
  GIVEN  functional Express.js API  
  WHEN I add my database name, MySQL username, and MySQL password to an environment variable file  
  THEN I am able to connect a database using Sequlize  
  WHEN I  enter schema and seed commands  
  THEN a development database is created and is seeded with test data  
  WHEN I enter the command line to invoke the application  
  THEN my server is started and the Sequelize models are synced to the MySQL database  
  WHEN I open API GET routes in Insomnia for categories, products, or tags  
  THEN the data for each of these routes is displayed in a formatted JSON  
  WHEN I test API POST, PUT, and DELETE routes in Insomnia  
  THEN I am able to successfully create, update, and delete data in my database
  <!-- Provide a short description explaining the what, why, and how of your project. Use the following questions as a guide:

  - What was your motivation?
  - Why did you build this project?
  - What problem did it solve?
  - What did you learn? -->

  ## Table of Contents

  <!-- Add a table of contents to make it easy for users to find what they need -->
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Questions](#questions)


  ## Installation
  Node.js, dotenv, express.js, mysql2, and sequelize packages are required to run this application.  
  To run this application, follow these steps:
  1. Put your mysql credentials in a .env file
  2. Open a command line and run 'mysql -u root -p' and enter your password
  3. Type 'SOURCE db/schema.sql' to create the database and tables
  4. Type 'USE ecommerce_db' to select the database
  5. Exit mysql
  6. Run 'npm run seed' in the command line to populate the database
  7. Run 'npm run watch' to start the server
  8. Open Insomnia or any suitable REST API client to navigate the routes

  <!-- What are they steps required to install your project? Provide a step-by-step description of how to get the development environment running. -->

  ## Usage
  To be used as a back end for an e-commerce website

  <!-- Provide instructions and examples for use. Include screenshots as needed.

  To add a screenshot, create an "assets/images" folder in your repository and upload your screenshot to it. Then, using relative filepath, add it to your README using the following syntax:

  "md
  ![alt text](assets/images/screenshot.png)
  " -->
  ## License
  Covered under the MIT License


  <!-- The next section of a high-quality README file is the license. This lets other developer know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicence.com/). -->


  ## Contributing
  To contribute, please contact me in the questions section

  <!-- If you would like other developers to contribute to your project, you can include guidelines
  for how they can do so. The Contributor Covenant(https://www.contributor-covenant.org/) is an
  industry standard, but you can always write your own.-->

  ## Tests
  [Link to walkthrough](https://drive.google.com/file/d/1xEtdq2piGnK0OvHRNENU9fK4u8MO3iJy/view)

  <!-- Go the extra mile and write tests for your application. Then provide examples on how to run them here. -->

  ## Questions
  A link to my [GitHub Profile](https://www.github.com/iab-19)

  If you have any questions, please reach out to me via email: iab.jr10@gmail.com.


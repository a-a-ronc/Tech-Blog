[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Sources](#sources)
  - [GitHub](#github)
  - [Development](#development)

## Description
This is supposed to be a tech blog site. Articles, blog posts, thoughts and/or opinions are supposed to be able to be posted here. The homepage should inclde existing blog posts if any have been posted as well as any navigation links for the homepage and dashboard. Should be prompted to sign in or sign up when any links are clicked in the navigation. When the sign up is clicked, the user should be prompted to create a username and password. When signed in, navigation links to the homepage, dashboard and option to log out should be shown. When the user clicks on an existing blog post, the existing posts should include the post title and date created. The user should also be left with the option to add a new blog post. When the user clicks on the button to add a new blog post he/she/they is prompted to enter both a title and contents for my blog post. When a user clicks on the button to create a new blog post, the title and contents of the post are saved. User is taken back to an updated dashboard with the new blog post. When one of the existing posts in the dashboard is clicked,the user is able to delete or update the post and is taken back to an updated dashboard. When the logout option is clicked in the navigation the user is signed out of the site. When the user is idlefor more than a set time, they are able to view posts and comments but is prompted to log in again before they can add, update, or delete posts. 

## Installation
<!-- Thanks to NPM, installation is pretty simple. Simply clone the repository and then run `npm i` without any arguments, and that will install everything in the dependencies. This will automatically create the node modules. This will use version pinning to make sure whoever uses the code gets the same versions of our libraries that we are using. Don't forget to access mysql to get the correct authorization to access the functionality of this application. 
Please change the .env file to contain your credentials for the database, and rename the file to `.env` -->

First, clone the repository
`$ git clone <repo-link>`
Enter the repository through your command line
`$ cd <repo-name>`
Then insert your DB credentials into your .env file
Finally, install the dependencies
`<repo-name>$ npm i`

## Usage
There is a development script and a production script. Development uses nodemon to watch for changes and automatically restart the script upon noticing changes. For production simply use node.

### Development
`<repo-name>$ npm run dev`

### Production
`<repo-name>$ npm start`

## License
This project is licensed under the MIT license.
Please refer to the license badge at the top of this document.

## Sources
Assistance received from exemplary individuals like Jaytee Padilla, Tom Gold, and Karina Guerrero
Express documentation
Handlebars Documentation
Student mini project examples

## GitHub

## Development

### Rough List
This is a rough list of things that need to be implemented in order for this project to function:
- [x] host a web server with express
- [x] talk to the database
- [x] create an account and have the info populate into the database
- [x] log in (create cookie) & log out (destroy cookie)
- [x] conditionally show content if user is logged in (check cookies)
- [x] check account page for account information
- [x] show previous purchases on account page

### TODOs
Things that need to be done with the existing codebase.

So the required functionality is not all there. I essentially got our project and made modifications to match the application requirements. I cleaned up the files but the only functionality that is missing is the ability to login. Everything else works. It would also be nice to implement some cleaner styling so that it looks pretty. 

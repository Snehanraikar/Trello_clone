# Trello_clone

Installation and Usage on Local Machine
Clone the repo:
$ git clone https://github.com/vijaygehlot/trello-app-clone.git

Add parameters in order to connect to MySQL on your machine:
Inside /index.js paste this block of code, change user and password and save the file:

// Mysql Configuration---
var connection = mysql.createConnection({
  host: "localhost",
  user: "<USER_NAME>",
  password: "<USER_PASSWORD>",
  database: "<DB_NAME>"
});
Install server-side dependencies:
$ npm install
Build the app:
$ npm run build
Run the server:
$ node index.js

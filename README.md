# NYT-Mongo-Scraper
This is a Node.js application that utilizes Cheerio and a MongoDB back-end to scrape and save NYT articles to a Bootstrap UI.

# Feature Overview
Scrape the New York Times homepage, then save and add notes to your favorite articles using this responsive application.

# NYT Scape Demo

For a live example, see a deployed version to Heroku at 

# Downloading This Application
To use this application:

Ensure that Node.js, npm, and MongoDB are installed on your machine. For instructions, see the Technologies Used section below.

Next, clone this repo to your local machine:

git clone <this repo>
Open the repo and execute the following in the bash terminal. Doing so should install the application's dependencies:
npm i
Then run the application from the command line:
node server.js

# Technologies Used
Node.js and npm. This application relies on both Node.js and npm to download Node packages and to run the application. 
MongoDB - This application assumes users have already installed MongoDB. Installation instructions can be found on the MongoDB website.
NPM Packages
This application utilizes the following NPM packages:

express
express-handlebars
mongoose
body-parser
cheerio
request
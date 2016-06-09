# Rest-API-in-Node.js-Mongo
Rest API in node.js + Mongo DB

Create REST webservices in node.js by using mongodb.

#System Requirement
+ Apache Server
+ Node.js
+ Mongo DB

# Installation Guide
+ Apache Server

sudo apt-get update
sudo apt-get install apache2 

+ Node.js
https://nodejs.org/en/download/

Installation via package manager
https://nodejs.org/en/download/package-manager/

+ Mongo DB
https://docs.mongodb.com/manual/installation/

# Setup Guide
+ Download or clone these files.
+ All packages and dependencies are define in package.json file, you have to run command npm install to load all required node modules and if you want to update the version of modules then you have to run command npm update.
+ After package installation create node.js server
+ start node.js server
  + Switch to the project directory Eg: cd /var/www/html/node-project
  + Then run command: node file_name.js

+ Then run services Eg: http://localhost:3000/users.json (here users is collection name)
+ This rest API uses GET, POST, PUT, DELETE methods to fetch, add, update and delete data.

# Services Example
+ http://localhost:3000/:collection.json
+ http://localhost:3000/:collection/(:_id).json


# Author
## Siddharth Pandey
Email: <a href="mailto:codebuckets@gmail.com">codebuckets@gmail.com</a>

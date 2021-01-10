# CovidProof by Technowiz
-The dependencies folder contains important files without which the web app won't run. 
-The Mysql Database folder contains all the sql schema and data required for the app. 
-The node_modules folder contains required modules to run an app made using node.js.
-The public folder contains the images, font files , javascript files and the css files required to render each page of the website.
-The views folder contains all the .ejs files of the respective pages.
-app.js is the place where all the connection between retrieval and insertion of information into the database takes place ie basically it is the file dealing with database connectivity.
-The rest of the files are the ones usualy present by default in any web application.
-Lets move on to how this app can be run.
-After downloading all the files open mysql workbench on the computer and import the database folder.
-Run xampp on your computer select mysql to be running on port 3307.
-Open command prompt and navigate to the directory where all these files are situated and type "node app.js" and check if it gets connected and running.
-Open browser and navigate to localhost:3000.
-Check the various functionalities of our application. 
-For logging in and other searching activities, refer to the username and passwords already inserted inside the database for correct authentication.
-Hope you enjoy using our app. 

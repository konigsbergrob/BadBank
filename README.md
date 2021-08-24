# BadBank

Project Title: 
Rob's Full Stack Bad Bank!

Description/Motivation: 
This project was created as part of the MIT xPro Professional Certificate in Coding: Full Stack Development with MERN. I previously created a "Bad Bank," but it was only a front end application. This is now full-stack. It allows users to create accounts at this bank, login, make deposits, make withdrawls, view your balance, and even view all user's data. However, authentication will be added at a later date, intended as my capstone project. 

Installation Guidelines: 
1) Download my repository
2) Setup your machine properly. Start with running "npm init" then "npm install express" and "npm install mongodb" 
3) Setup a container for the database (NOTE: you will need Docker desktop installed and setup). Run "docker run -p 27017:27017 --name badbank -d mongo"
   NOTE: this will setup the database side of the application (port 27017). If you run it multiple times, you'll need to delete the first instance. 
4) Run "node index.js"

Any potential errors should come from having the correct packages/programs. Inspect the package.json file if necessary! 

Screenshots: 
Screenshots of making a new account, depositing to this new account, and a list of new accounts after creating in the terminal are below. 
![Deposit](https://user-images.githubusercontent.com/76491829/130537005-70d50dde-cbfe-4c34-8005-bc3d63deedc3.JPG)
![New Account](https://user-images.githubusercontent.com/76491829/130537006-0ed2b0a4-6153-49a1-8cac-0ebd314b67fe.JPG)
![ProjectInAction](https://user-images.githubusercontent.com/76491829/130537007-10f6e537-f5d9-4806-8a83-6ab87b928317.JPG)


Technology used: 
Client/Browser: Google Chrome (browser), React (front-end) 
Server: NodeJS, Express
Database: MongoDB, Docker

Features: 
This "bad bank" allows you to create new users, login to a single user, and deposit and withdraw from individual accounts. There is also a page to see a user's balance, and a page with all data (essentially all transactions in the bank). Future features include authentication/authorization so that all data is not public. 

License: The MIT License | Open Source Initiative. 

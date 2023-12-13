## GoGoShip Parcel Delivery Service Application (Group-8) 

# The project developers:  
The project is being worked on by Oulu University of Applied Sciences (OAMK) second-year information technology students and we have been working together in the whole project:
1. Hu Yiming HuYiming2023 (HuYiming) (github.com)
2. Zhenni Pan ZhenniPan1213 (ZHENNI PAN) (github.com)
3. Ruimin Luo ruimin01 (github.com)
4. Shamima Shammi Shammioamk (Shamima Shammi) (github.com)

# Introduction of the project: 
The GoGoShip is a web-based application that simulates an automated parcel delivery locker system. The system includes applications for consumer users, delivery drivers, a parcel locker touchscreen simulator, and a parcel generator ‘’robot”. Parcels are transported more efficiently from senders to receivers with the help of a parcel delivery service, guaranteeing prompt and safe delivery. These services provide easy door-to-door solutions for both consumers and corporations by utilizing a network of carriers. This test plan outlines the testing approach, test cases, and requirements for ensuring the system's functionality, performance, and security.  

# Description of the project work:
 The project was created using the Agile software development methodology, and it was implemented using the Kanban framework template included in GitHub Projects. Our team has maintained continuous communication throughout the project, and it has advanced according to plan. Our team has been using Teams to communicate remotely and on campus equally. Additionally, we have been able to attend the weekly teacher meetings. In general, our team has demonstrated self-organization, communication, and the ability to produce applications that are functional and meet project criteria.

# Technologies used in the project:
1. User Interface: We designed a draft in notebook pen and tried to proceed accordingly for save time.
2.Front-end:
 a. React.js Framework
3.Back-end:
 a. Node.js
 b. Express.js
 c.Axios.js
4. Database:
 a. MySQL
5. Deployment:
 a. Microsoft Azure Cloud Service
6. Testing:
 a. Selenium
 b. Postman
 c. JIRA
 
# Implementation tools for the Project:
1. Version Control System: Git & GitHub
2. Project Management Tool: Kanban Board
3. Code Editor: Visual Studio Code
4. API Testing: Postman
5. Database Design Tool: MySQL Workbench

# The architecture of The Project:
 
# Project Interface Description:
In this project, three parts of the front-end portion have been worked such as consumer user’s application, driver application and touchscreen view. For these three parts, we developed one backend and store date in database. We create a parcel generator robot, which shows how a parcel can be automatically created. We also use testing. 
1. Consumer user application:
 This part we have added register and login functionality for users. After login, a user can create parcel according to his/her needs, delete own account, track parcels, view the history of receiving or sending parcels and users also receive reminders when there is a parcel waiting to be picked up. 
2. Driver application: 
This application created for parcel delivery man called driver. Driver needs to login this website first. After login, driver can select lockers, view which cabinets are empty, choose which parcels need to be kept in the cabinet, which parcels need to be picked up for delivery and completing parcels pickup or keep driver must change the parcel status. After finishing driver has to logout. 
3. Touchscreen application: 
The touchscreen application simulates interactions with five parcel lockers. Users can select a locker, enter a four-character pickup code to open the cabinet door for pickup, with an option to close the door after completion. Similarly, users can enter a send code to open the door for delivery, with a completion button to finalize the operation. The system provides feedback on successful or incorrect code entries and recognizes if the correct code was entered at the wrong locker.

# Testing: 
In the automated testing phase, the front-end React application underwent testing for two consumer functionalities: user registration and login. The back-end API was tested for three endpoints, covering registration, login, and account deletion. Additionally, automated tests were conducted for rendering components related to the touchscreen functionality.
Link of this Test Document:
https://github.com/AWAP-Group8/Test-plan-document.git

# Deployment:
For deployment, we use Microsoft Azure Cloud Service. We deploy all front-end such as consumer user application, driver service application, touchscreen application and backend logic.

# Project link:
1. GitHub Link: https://github.com/orgs/AWAP-Group8/repositories
2. Front-end application links:
 a. Consumer users: https://consumer-application-frontend.onrender.com/
 b. Driver:  https://icy-field-03e7c6b03.4.azurestaticapps.net
 c. Touchscreen: https://touchcreen-frontend.onrender.com
3. Back-end logic link: https://gogoship.azurewebsites.net

# How to install and use this Application:
1. Step 1:
Clone the project form the project repository.
2. Step 2:
Install the following dependencies:
a. Axios.js
b. Bootstrap
c. react
d. React-dom
e. React-router-dom
f. Stream-http
g. Stream-browserify
3. Step 3:
Go to the server folder and do: npm init-y and npm install express.
Install the following dependencies:
a. Chai
b. Chai-http
c. Mocha
d. Cors
e. Dotenv
f. Express
g. Express-jwt
h. Jsonwebtoken
i. Mysql 
j. Nodemailer

4. Step 4:
Create local database: Start mysql and create a database.js file in the server folder and modify the “aaa” portion as needed:
const mysql = require(“mysql”)
const connection = mysql.createConnection({
host: “aaa”
user: “aaa”
password: “aaa”
database: “aaa”
});
module.exports = connection;
5. Step 5:
When start application, run the following command:
cd server
node index.js
cd ..
npm start


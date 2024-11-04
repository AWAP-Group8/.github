# GoGoShip

# The project developers:  
The project is being worked on by Oulu University of Applied Sciences (OAMK) third-year information technology students and we have been working together in the whole project:
1. Hu Yiming HuYiming2023 (HuYiming) (github.com)
2. Pan Zhenni ZhenniPan1213 (ZHENNI PAN) (github.com)
3. Shamima Shammi Shammioamk (Shammioamk) (github.com)
4. Luo Ruimin ruimin01(ruimin01) (github.com)
   
# Introduction of the project: 
GoGoShip is a web-based application that simulates an automated parcel delivery locker system. The system includes applications for `consumer users`, `delivery drivers`, a `parcel locker touchscreen simulator`, and a `parcel generator "robot"`. Parcels are transported more efficiently from senders to receivers with the help of a parcel delivery service, guaranteeing prompt and safe delivery. These services provide easy door-to-door solutions for both consumers and corporations by utilizing a network of carriers. This test plan outlines the testing approach, test cases, and requirements for ensuring the system's functionality, performance, and security.  

# Description of the project work:
The project was created using the Agile software development methodology, and it was implemented using the Kanban framework template included in GitHub Projects. Our team has maintained continuous communication throughout the project, and it has advanced according to plan. Our team has been using Teams to communicate remotely and on campus equally. In general, our team has demonstrated self-organization, communication, and the ability to produce applications that are functional and meet project criteria.

# Technologies used in the project:
## User Interface: 
   We designed a draft in notebook pen and tried to proceed accordingly for save time.
## Front-end:
   - `React.js`
   - `Framework`
## Back-end:
   - `Node.js`
   - `Express.js`
   - `Axios.js`
## Database:
   - `MySQL`
## Deployment:
   - `Microsoft Azure Cloud Service`
   - `Render Service`
## Testing:
   - `Selenium`
   - `Postman`
   - `JIRA`

# Implementation tools for the Project:
- Version Control System: `Git & GitHub`
- Project Management Tool: `Kanban Board`
- Code Editor: `Visual Studio Code`
- API Testing: `Postman`
- Database Design Tool: `MySQL Workbench`

# The architecture of The Project:
<img width="452" alt="image" src="https://github.com/AWAP-Group8/consumer-application-frontend/assets/143256533/3af80d1f-4ab2-4c0c-927a-69cbcc33fea9">

# Project Interface Description:
In this project, three parts of the front-end portion have been worked such as `consumer user’s application`, `driver application` and `touchscreen view`. For these three parts, we developed one backend and store date in database. We create a parcel generator robot, which shows how a parcel can be automatically created. We also use testing. 

# Testing: 
   - `Selenium`
   - `Postman`
   - `JIRA`
  
# Deployment:
For deployment, we use Render and Microsoft Azure.

# Servers running the project:
driver: `https://icy-field-03e7c6b03.4.azurestaticapps.net`

consumer: `https://consumer-application-frontend.onrender.com/`

touchscreen: `https://touchcreen-frontend.onrender.com/`

# Project link:
1. GitHub Link: `https://github.com/orgs/AWAP-Group8/repositories`
2. Front-end application links:
   
   a. driver: `https://github.com/AWAP-Group8/driver-application-frontend`
   
   b. consumer: `https://github.com/AWAP-Group8/consumer-application-frontend`
   
   c. touchscreen: `https://github.com/AWAP-Group8/touchscreen-application-frontend`
4. Back-end logic link: `https://github.com/AWAP-Group8/backend`


## How to install and use this Application:
### Step 1:
  `Clone` the project form the project repository.
  
### Step 2:
  #### Install the following dependencies:
    Axios.js
    Bootstrap
    react
    React-dom
    React-router-dom
    Stream-http
    Stream-browserify
    
### Step 3:
  Go to the server folder and do: `npm init-y` and npm install express.
  #### Install the following dependencies:
  - Chai
  - Chai-http
  - Mocha
  - Cors
  - Dotenv
  - Express
  - Express-jwt
  - Jsonwebtoken
  - Mysql 
  - Nodemailer

### Step 4:
  #### Create local database: Start mysql and create a database.js file in the server folder and modify the “aaa” portion as needed:
    const mysql = require(“mysql”)
    const connection = mysql.createConnection({
    host: “aaa”
    user: “aaa”
    password: “aaa”
    database: “aaa”
    });
    module.exports = connection;
    
### Step 5:
  When start application, run the following command:
   - cd server
   - `node index.js`
   - `cd ..`
   - `npm start or yarn start`

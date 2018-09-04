# HotelSearch-DATABASE-MongoDB

----------------------Contributors-------------------------------------------

1. Smriti Srivastava : WebUI (Angular) - Hotel Search page, UI Design in Hotel-Search and Documentation Page. Integration of Both the components in Angular.
2. Rajpreet Singh Nayyar : Complete UI Design, Responsiveness (Hotel-Search Page and Documentation Page), Part of functionality in HotelSearch Page (Angular) 
3. Ankita Sharma : Database Setup and complete connectivity with the Angular project in MongoDB, Integration with angular app and NodeJS.
4. Pallvi Goel : Complete functionality in Documentation Page (Angular) and integration of all the components along with database.
5. Anushka Sherawat : Complete functionality in Documentation Page (Angular) and integration of all the components and reveiwed final code.
6. Shrijeet Karade : UI Design and functionality, NodeJS, testing and final overlook at the code.
7. Bhargavi Deshpande : Implemented complete Testing using Jasmine-Karma framework and integrated in the project.
-----------------------First we have to setup Node---------------------------

Install node from https://nodejs.org/en/download/
-npm init
latest versions

----------------------Then we have to setup mongoDB--------------------------

Step 1: Goto www.mongodb.org and download mongodb setup .exe.
Step 2: While installing mongodb, go for complete setup type.
Step 3: Goto local disk C: and create a folder name "data". Inside this data folder make a folder named "db".
Step 4: After complete installation, navigate to 
	"c:program files/mongodb/server/4.0/bin"
	and open cmd(command prompt) here.
Step 5: In cmd, execute the following command:
	"mongod"

----------------------Then we have to setup express---------------------------

Navigate to app.js folder and open cmd and execute the following commands:
"npm install --save mongo"
"npm install --save express"
"npm install --save path" 
""npm install file-system --save"

Open a terminal inside 'HotelAssignment_Database' folder.
In cmd, execute the following command:
"node app.js" 

--------------------Then we have to setup Angular CLI-------------------------

step 1: Navigate to project Directory: 
step 2: Install Angular CLI by using Node Packet Manager "npm install -g @angular/cli"
step 3:Run "npm install" to include nodemodules in project. 

----------------------To Start the Project---------------------------------

step 1: Start server by using following command "ng serve"
step 2: Open the browser and enter the URL localhost:4200

----------------Then we have to setup Jasmine and karma-----------------------

 You don't need to install any such libraries for Jasmine and Karma as it install's with Angular ClI 

----------------------To See the TestResult Output--------------------------------- 

step 1: Navigate to project Directory
step 2: Run "ng test" 
step 3: Karma server window will appear where you will find the number of testcases for components with result
step 4: In cmd also you will get the result of testcases



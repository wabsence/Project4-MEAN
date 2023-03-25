# PROJECT DOCUMENTATION

## Step 1: BACKEND CONFIGURATION


#### Command: sudo apt update (update ubuntu packages)
#### Output:

![Update](images/update.png "packages update process")

#### Command: sudo apt upgrade (upgrade ubuntu)
#### Output:

![Upgrade](images/upgrade.png "ubuntu upgrade process")

#### Command: sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificate (Add Certificate)
#### Output:

![addCertificate](images/addCertificate.png "Add Certificate")

#### Command: curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - (getting node.js location from ubuntu)
#### Output:

![nodeLocation](images/nodeLocation.png "node location")

#### Command: sudo apt-get install -y nodejs (installing node and npm)
#### Output:

![nodeNPM Installation](images/nodeNPM.png "nodeNPM Installation")

## STEP 2:  MongoDB Installation
#### Checking if service is up and running

![Mongodb Installation](images/mongodbStatus.png "Mongodb Installation")

#### Body-Perser Installation

![Body-Parser Installation](images/bodyParser.png "Body-Parser Installation")

#### Create a Books Directory and run npm init.

![Books Init](images/bookInit.png "Books Init")

#### Create a server.js file

![ServerJS](images/serverJS.png "ServerJS File")

## STEP 3: INSTALL EXPRESS AND SET UP ROUTES TO THE SERVER

#### Express and Mongoose Installation
![Express_Mongoose](images/expressMongoose.png "Express_Mongoose_Installation")

#### create routes.js file in apps directory

![routesJS File](images/routesJS.png "routesJS File")

#### create book.js file in models directory

![Models](images/bookJS.png "Models")

## STEP 4: ACCESS THE ROUTES WITH ANGULARJS

![Angular](images/scriptJS.png "Angular Script")

#### Create index.html File

![indexHTML File](images/indexHTML.png "indexHTML File")

#### Modify the route.js file using asyn/wait callback of javascript for all the end point to work (i.e Get, Post and Delete)

![routesJS File](images/routesJS2.png "routesJS File")

#### Add Port 3300 to inbound rule of Security Group.


![Add_Port_3300](images/port3300.png "Add Port 3300")

#### Start server
![startServer](images/startServer.png "Start Server")

#### Access via Browser

![accessBrowser](images/output.png "Access  via Browser")

#### Add a new book
![Add_Book](images/output2.png "Add Book")

#### Terminal Output

![Add_Book](images/terminalOutput.png "Add Book")

![View_Record](images/Output3.png "View Reord")

#### Add a new book
![Add_Book](images/output4.png "Add Book")

#### Terminal Output
![Add_Book](images/terminalOutput2.png "Add Book")

![View_Record](images/Output5.png "View Reord")








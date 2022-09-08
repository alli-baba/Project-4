# Project 4 Documentation

#   Updating ubuntu

`sudo apt update`

![Updating ubuntu](Images/Update ubuntu.png)



#   Upgrading ubuntu

`sudo apt upgrade`

![Updating ubuntu](Images/Upgrade ubuntu.png)


#    Adding certificates


`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`


![Adding certificates](Images/Adding certificates.png)

#   Installing NodeJS

`sudo apt install -y nodejs`

![Installing NodeJS](Images/Install NodeJS.png)


#   Installing MongoDB

`sudo apt install -y mongodb`


![Installing MongoDB](Images/Installing MongoDB.png)


#    Starting The server

`sudo service mongodb start`


![Starting The server](Images/Starting the server .png)


#    Verify that the service is up and running


`sudo systemctl status mongodb`


![Verify that the service is up and running](Images/Verifying that the service is up and running.png)


#    Installing npm and Initializing npm project


`sudo apt install -y npm`  `npm init`

![Installing npm](Images/Initializing npm project.png)

#  Installing body-parser package


`sudo npm install body-parser`


![Installing body-parser package](Images/Installing body-parser package.png)


#  Creating a folder named ‘Books’ and adding file server.js


`vi server.js`

![Creating a folder named ‘Books’ and adding file server.js](Images/Adding a file to it named server.js.png)


#   Installing Express and set up routes to the server


`sudo npm install express mongoose`


![installing express mongoose](Images/installing express mongoose.png)


#   Creating a file named routes.js

`vi routes.js`

![Creating a file named routes.js](Images/Creating a file named routes.js.png)


#     Creating a file named book.js

`vi book.js`


![Creating a file named book.js](Images/Creating a file named book.js.png)


#    Starting the server

`node server.js`

![Starting the server](Images/Starting the server.js.png)

#     Web Book Register Application

  `http://44.201.193.182:3300`


![Web Book Register Application](Images/Book Register web application.png)


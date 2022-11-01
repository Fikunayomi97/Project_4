# Project_4 Documentation

### After logging into my instance, i updated and upgraded the machine

`sudo apt update`

![updating](./Images/apt-update.PNG)

`sudo apt upgrade`

![upgrading](./Images/apt-upgrade.PNG)

### I went ahead to add certificates

`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`

![adding-certificates](./Images/certificates-1.PNG)

### Installing node js

`sudo apt install -y nodejs`

![installing-nodejs](./Images/installing-node-js.PNG)

### I went ahead to install mongodb

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`

`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`

`sudo apt install -y mongodb`

![installing-mongodb](./Images/Installing-mongodb.PNG)

### I started the server and checked to make sure its running

`sudo service mongodb start`

`sudo systemctl status mongodb`

![starting-mongodb](./Images/starting-mongodb-server.PNG)

### I installed npm (node package manager)

`sudo apt install -y npm`

![installing-npm](./Images/installing-npm.PNG)

### Installing body parser to help process json files

`sudo npm install body-parser`

![installing-body-parser](./Images/Installing-body-passer.PNG)

### Went ahead to install express mongoose

`sudo npm install express mongoose`

![installing-express-mongoose](./Images/Installing%20mongoose.PNG)


### starting the server

`node server.js`

![starting-server](./Images/server-running.PNG)

### I opened TCP port 3300 and the used the public IP to access the app on my browser

![book-app](./Images/books-app.PNG)
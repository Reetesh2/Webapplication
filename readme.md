# Web Application
A nice project with a nice description

---
## Requirements

For development, you will only need Node.js and a node global package, npm, installed in your environement.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###
### Yarn installation
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---



## Install

    $ git clone https://github.com/YOUR_USERNAME/Webapplication
    $ cd webapp
    $ npm install
###need to Unzip webapp project and open webapp folder present in vs code or any ide then perform NPM install and other things

## Configure app

Open `.env` then edit it with your settings. You will need:

please change the passwords for database 

## Running the project

    $ node app.js

## Simple build for production

    $ npm build
    
   ### require post man to send the request and receive the output 
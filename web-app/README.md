# Project Aegis

This repository deals with door security management from the web application. This repository contains the frontend of the web application.

**Installation**

clone this repositiry or download the zip file.<br />

```git clone https://github.com/ZeMoSoLabs/aegis-ui.git```

**Build docker images**

You can find ```dockerImageSetup.sh``` in the folder. <br />

First, give the permission to execute .sh file.

```chmod +x dockerImageSetup.sh``` <br />

Then, run the file to build and push the docker images into your docker.

```./dockerImageSetup.sh```

**Run docker-compose up**

Run the ```docker-compose up -d``` from the aegis-backend directory.

**See the application in browser**

Hurray !! Your application will be running in ```http://localhost:3000```.
# Boatmonitor
Boat Monitor to track location of a vehicle (boat) and status of its batteries. The project consists of an Arduino node for monitoring the vehicles position (using GPS) and voltage and temperature of the batteries. The results will be available in a browser and mobile web app. LoRaWAN, the long-range and power efficient communication technology, is used to transfer data from the node to the server.

### Project
This is the main repo of the project. It contains the documentation of the project and code fragments that are too small to have their own repo. Other related repo's are:
* [bhavers/boatmonitor_arduino](https://github.com/bhavers/boatmonitor_arduino) - Code for the Arduino component for the project
* [bhavers/boatmonitor_webapp](https://github.com/bhavers/boatmonitor_arduino) - Code for the web app based on Javascript and Node.js, running on IBM Bluemix.

## Document structure
* /docs - Documentation (architecture/design) of the project
* /cloudant - Code for views and indexes on cloudant database
* /nodered - Flows for nodered that contains APIs

## Team & planning
Project planning is done through ZenHub (see Boards menu choice).

# flow2-Node-RED
This repository contains the second excercise of Node-RED for the course of Internet of Things of Código IoT

# Introduction
This excercise connects an Inject node to a Function node to a Debug node to generate a TimeStamp every one second with the following format: "Day Month Date Year Hour:Minute:Second TimeZone". This action shows the use of the Debug tab.

# Material
To make this flow (program) you need:
* Computer
* [Ubuntu](https://releases.ubuntu.com/20.04/)
* [NodeJS](https://nodejs.org/es/)
* [NPM](https://www.npmjs.com/)
* [Node-RED](https://nodered.org/docs/getting-started/local)

# References
* [Node-RED Page](https://nodered.org/)
* [Running Node-RED locally](https://nodered.org/docs/getting-started/local)

# Instructions

### Previous requirements 
Run the following commands in a terminal to install Node.js LTS (v16.x):
* sudo apt install curl
* curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
* sudo apt-get install -y nodejs
Install build tools
* sudo apt-get install -y build-essential
Install de Node-RED
* sudo npm install -g --unsafe-perm node-red

### Environment preparation
Open Node-RED
* Open a terminal (DON NOT CLOSE, ONLY IF YOUARE DONE USING NODE-RED) and write: node-red
* Open a window in your web browser and write: localhost:1880

### Process
* Drag a Inject, Function and a Debug node to the Flow 2 page
* Connect nodes in the above order
* Doube clic the timestamp node and make the following configuration

![image](https://user-images.githubusercontent.com/83924529/187826036-c397f678-3caf-4dbf-af4f-0e52c1651f54.png)

* Deploy the program
* Debug
* Press the timestap square that is inside the node

![image](https://user-images.githubusercontent.com/83924529/187820416-0163c979-52bb-4f0a-a14b-aebd704a1c18.png)

* Date messages will show up every second in the Congig debug tab/area

![image](https://user-images.githubusercontent.com/83924529/187826179-50faa170-6df6-432f-82de-f809cd78bba1.png)

# Results
The following image shows the results for flow1 in Node-RED

![image](https://user-images.githubusercontent.com/83924529/187826210-d83743d9-0f99-4b27-a2cb-2ff5f33030a1.png)

# Evidence
The evidence is found in the flow2.json file, uploded in this repository

# Credits
Flow developed by Amy Malavar
* [GitHub](https://github.com/amymalavar)
* [LinkedIn](https://www.linkedin.com/in/amy-malavar)

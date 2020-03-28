# Nodered application for Schneider Electric products

Some nodered application I developed to be used with Schneider Electric products

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
1. Node.js
2. nodered
3. nodered modules will be dependent on the nodered application you are using

```

### Installing

A step by step series of examples that tell you how to get a development env running



```
1. Install Node.js, nodered and necessary nodered modules
2. Open up txt file
3. Copy all text by doing "Ctrl + A, Ctrl + C"
4. Start nodered by typing "node-red" into cmd
5. Once node red has started, go to localhost:1880 on web browser
6. Go to settings > import nodered flows
7. Paste copied text into pop up box by doing "Ctrl + V"
8. Save flow
```
### Flow Description

MA with HTTP and SQL: Connecting your PLCs, Sensors, HMIs, SQL databases and other smart devices to Ecostruxure Machine Advisor using HTTPs.

Nodered-for-harmony-hub: Collect data from Scheider Electric harmony hub (zigbee wireless hub) using modbus tcp/serial data (modbus module required: https://flows.nodered.org/node/node-red-contrib-modbus).

OPC UA with Augmented Reality: Connect to a OPC UA server to retrieve data to be displayed for Augmented Operator Advisor. For POC application. Not recommended for large scale deployment. (OPC UA module reqired: https://flows.nodered.org/node/node-red-contrib-opcua)

Telegram Node Red: Simple telegram bot for telegram notification. Can be used for manufacturing, machine, process alarms & events alerts (Telegram module required: https://flows.nodered.org/node/node-red-contrib-telegrambot)







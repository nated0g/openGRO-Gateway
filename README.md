# openGRO-Gateway

## About The Project

openGRO is an open source CEA (Controlled Environment Agriculture) platform.  This gateway is intended to be deployed on a Raspberry Pi or similar device, using [balenaOS](https://github.com/balena-os).

This consists of:
* Grafana for building monitoring dashboards 
* InfluxDB for storing sensor and configuration data
* Telegraf for inputting data into InfluxDB
* Mosquitto MQTT broker for messaging between services
* Node-Red for easy user-configurable logic
* Chisel TCP tunnel for remote access 


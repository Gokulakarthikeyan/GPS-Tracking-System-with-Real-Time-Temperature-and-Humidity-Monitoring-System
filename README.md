# GPS Tracking System with Real-Time Temperature and Humidity Monitoring System

## System Implementation

• Setup MQTT Broker: Install and configure the MQTT broker. Note down the broker's IP address and port.

• Install Node-RED: Install Node-RED using the package manager on your server or device. Access Node-RED through a web browser and configure it.

• Node-RED Flows: Create Node-RED flows to subscribe to MQTT topics where sensors publish data. Use the dashboard nodes to display temperature and humidity data.

• Connect Sensors: Connect temperature and humidity sensors to microcontrollers. Write code on the microcontrollers to read sensor data and publish it to MQTT topics.

• Install Grafana: Install Grafana using the package manager on your server or device. Access Grafana through a web browser and configure it.

• Configure Grafana Data Source: Add an MQTT data source in Grafana and provide the MQTT broker details.

• Create Grafana Dashboards: Design dashboards in Grafana to display temperature and humidity data. Use Grafana panels and widgets to visualize data in a meaningful way.

• Test the System: Deploy your system and monitor the temperature and humidity data in real-time through the Grafana dashboard.

• Optimize and Secure: Optimize your setup for performance and security. Consider implementing security measures for MQTT communication and access control for Node-RED and Grafana.


## Screenshorts

    Node-Red

   <img src= "">
    
    Maria-DB
    
   <img src= "">

    Grafana
    
   <img src= "">
# ttn-mapper-node
A node with GPS for use with TTN Mapper without the need of a smartphone.

This is the first commit of an Arduino Sketch for an GPS-Tracker to work with The Things Network an ttnmapper.org. This Sketch uses TinyGPS, the Arduino LMIC-Library by Matthijs Kooijmanand and the hartware serial of an Adafruit Feater LoRa. I use sample Code from Pieter Hensen https://github.com/Teumaat/ttn-tracker

The folder ttn contais the payload decoder for TTN.

TO CONTRIBUTE TO TTN Mapper:
 1. Register a new Application and/or new device on the
    TTN Dashboard (https://console.thethingsnetwork.org).
 2. Update the TTN decoder    
 3. Copy the correct keys into the the sketch.
 4. Make sure packets are arriving on the TTN console when your node is
    powered and in reach of a gateway.
 5. Share your Application ID, Access Key, Device ID and payload format with
    contribute@ttnmapper.org so that your measurements can be automatically
    imported into TTN Mapper.

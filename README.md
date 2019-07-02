# hack-a-stove
> this is a work in progress

This is my attemp to hack my little stove into an IoT device so I can switch it on/off from my local wifi

### Notes
* An MQTT Broker is needed for this to work
* An MQTT Client is also needed to publish
* Schematics soon

### Materials
* Weemos D1 R1 Mini
* 2 Relay Module
* PSU 220v > 5v
* The stove to destroy

### How to
1. Set your config.h
2. Upload hack-a-stove.ino
3. Set up a MQTT client 
4. Publish under topic: `stove/heat` on of these:
    * `L`: Low heater
    * `H`: High heater
    * `O`: Switch off heater

# Automated Room Humidifier System

A device that automatically detects the room humidity and turns on/off humidifier to control the humidity in the range comfortable for humans. 


## Summary

The automated Room Humidifier System is an enhanced humidifier that controls the room humidity in a certain level claimed by the user. The Arduino controls the power state of the humidifier and connects the system to the cloud. Its website enables users to remotely turn on/off the humidifier or set it to automatically work based on the current room humidity. The users are able to set a specific range that they feel comfortable working in. The arduino will detect the room humidity with its connected sensor. It will keep the power off if the humidity level is within or higher than the range, and turn the power on if it is lower than the range until it reaches. 

The main goal of the project is to deliver a trouble-free experience of humidifying the environment in winter. People don't need to worry about when it is the right time to turn off the humidifioer or turning on when they already started to feel uncomfortable. By setting a range and keeping the system on, everything is automatically under control in the background. 


## Component Parts

The hardware includes the arduino itself attached to the humidifier as an intelligent switch.

- A relay: controlling the power of the humidifier. (OUTPUT)
- A humidity sensor: detecting the room humidity. (INPUT) I will purchase this item if the hybrid lab doesn't have it.
- A Wi-Fi chip: enabling user control of the power state and humidity range. (INPUT/OUTPUT)

The software includes a web client that displays the power state 

- A switch: controlling the on/off state of the humidifier. (INPUT)
- A slider: controlling the humidity range in which the humidifier works. (INPUT)
- A database: storing the humidity range claimed by the user. (DATA)

### Block Diagram

![alt text](https://github.com/Spidmax/Final-Project/blob/master/Diagram.jpeg)

## Challenges
1. I don't understand how to make Arduino work under high voltage that the humidifier requires. I will research to make sure that there would be no safe concerns.
2. I am not familiar with the network connection feature either. I will research and determine how to build the background online structure. (database, if it is necessary to include a user-login feature, etc.)


## Timeline

Week 1: Borrow the Wi-Fi Arduino & make sure it works properly, order the necessary sensors <br/>
Week 2: Prototype the circuit with sensors and devices <br/>
Week 3: Build the website, connect with the system, make it functional <br/>
Week 4: Include real devices, test & iterate the circuit, debugging <br/>
Week 5: Present the final project.

## References and link

https://thecustomizewindows.com/2017/10/arduino-temperature-humidity-sensor-new-dht11-dht21-dht22-tests/ <br/>
http://www.instructables.com/id/Controlling-AC-light-using-Arduino-with-relay-modu/ <br/>
http://arduino-info.wikispaces.com/TemperatureHumidity <br/>
https://docs.particle.io/guide/getting-started/start/photon <br/>
http://www.instructables.com/id/PhotonConnect-LCD-With-I2C/ <br/>
https://www.hackster.io/moritz/measuring-temperature-and-humidity-with-particle-photon-f1c300

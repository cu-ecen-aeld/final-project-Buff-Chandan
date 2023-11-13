# final-project-Buff-Chandan

# Overview
In this project, a prototype of a Weather reporting system for a Greenhouse farm is expected to be deisgned and implemented.
The readings from a temperature sensor and humidity sensor will be used to monitor the internal environment of the greenhouse farm. Here, the values of the sensors would be accessed and displayed for analysis.

The SHT21 sensor would measure the temperature and the HTU21 sensor would measure the humidity from the designated atmospehere. The project is intended to be built on a Beaglebone Black board platform. And the sensors shall use I2C protocol.

The image for the Beaglebone Black will be created with Buildroot and include necessary drivers and applications to communicate with the modules and provide methods to access the data collected.

# Goals
To prepare a compact, low cost, low power, and portable system.
Easy and quick to assemble and configure.
Provide most possible accurate readings via the sensors.

# Motivation
Recently there has been a increase in the awareness among the people regarding health. The most important aspect is what we feed into our bodies. Organic farming is considered to be one of the best methods to grow nutritious food. But we need a good culture medium to grow plants in a controlled environment to maintain a economically feasible model of farming. Humidity and temperature are two main aspects of it.

In this project I intend to learn about:
1. Build image of the Beaglebone Black board.
2. Gain hands-on practice on Beaglebone Black board to build the project on buildroot.
3. Intergate the sensor based on I2C protocol.
4. Display the readings of the sensor on the console. 

# Block Diagram

![AESD PROJ BLK](https://github.com/cu-ecen-aeld/final-project-Buff-Chandan/assets/113010098/26138e51-c1e5-4912-8e8c-7995eb897a3c)

# Targeted Build System
I  intend to use Buildroot build system to implement the project.

# Hardware Platform
1. Beaglebone Black
2. SHT 21 sensor
3. HTU 21 sensor

# Open Source Projects Used
I am still exploring means and methods.
[Buildroot](https://buildroot.org/)  
[BBB-linux-app](https://github.com/nghiaphamsg/BBB-linux-app/tree/master) 

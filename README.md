# Arduino-LabView-Weather-Station

## Introduction 
Nowadays, the need for real-time information on local environmental parameters is very important. With this project I provide this information in a simple way to all people who want to be informed about the weather situation on a regular basis. In this work I realized a weather station that measures some existing physical phenomena. 
This station will be connected to the LabVIEW interface. Overall, the station includes 2 sensors such as: temperature sensor and humidity sensor. An acquisition card based on Arduino UNO is used to process the measured data from these sensors and transfer them to LabVIEW. 
My experimental project thus consists in realizing a real-time measurement system of these physical quantities. The data are processed in the processing and control unit based on the Arduino UNO, in order to transfer them to LabVIEW using LINX (LINX is an open source project of Digilent and is designed to facilitate the development of embedded applications using LabVIEW). 

## Software/hardware used 

###### *DHT11 Sensor: DHT11 Module (Digital Humidity and Temperature Sensor)
This DHT11 temperature and humidity sensor has a digital signal output calibrated with the complex of temperature and humidity sensors. Its technology ensures high reliability and excellent long-term stability. A high-performance 8-bit microcontroller is connected. This sensor includes a resistive element and a temperature sensing wet NTC measuring instruments. It has excellent quality, fast response, anti-interference capability and high performance advantages.
###### *Labview 
###### *ARDUNIO 
###### *lNX
INX is an open source project by Digilent and is designed to make it easy to develop embedded applications using LabVIEW. LINX includes VIs for over 30 of the most common embedded sensors as well as hardware agnostic APIs for accessing peripherals like digital I/O, analog I/O, PWM, I2C, SPI, and UART.
Whether you’re remotely controlling a chipKIT or Arduino over USB/Serial, Ethernet or Wi-Fi, or deploying VIs to run on BeagleBone Black or Raspberry Pi 2/3, LINX and LabVIEW make it easy visualize the data you’re working with, debug your code, and create advanced embedded applications faster than ever before.

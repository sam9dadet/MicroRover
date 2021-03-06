# Micro Rover
Adapted from [Rick's Trinket Rover](https://github.com/rwinscot/TrinketRover), estimated build time: 3 hours.
![Image of Prototype](https://raw.githubusercontent.com/six0four/MicroRover/master/images/prototype.jpg)

## Table of Contents
1. [Introduction](https://github.com/six0four/MicroRover#1-introduction)
2. [Bill of Materials and Required Tools](https://github.com/six0four/MicroRover#2-bill-of-materials-and-required-tools)
3. [Instructions](https://github.com/six0four/MicroRover#3-instructions)
4. [Future Development](https://github.com/six0four/MicroRover#4-future-development)

## 1. Introduction
A common introduction to microcontrollers is through the [Lego NXT ROBOTC Curriculum](http://www.education.rec.ri.cmu.edu/previews/robot_c_products/teaching_rc_lego_v2_preview/home/ROBOTC_Curriculum_Outline.pdf). This project aims to use a low cost platform to also explore microcontrollers. Similarly, a small rover is assembled as the vehicle. Currently the small rover moves forward until an object reflects infrared light which triggers it to reverse and turn before continuing forward again.

## 2. Bill of Materials and Required Tools
For a list of materials please see the Excel file in the repository.

Regarding tools, the following are a minimum:
- Safety glasses.
- Soldering iron and lead free solder (to be added to materials list).
- Small side cutting pliers.
- Small Phillips screw driver.

## 3. Instructions
1. Soldering guidance:
	1. Start off by watching some ahort soldering guidance videos: [NASA Jove Project](https://radiojove.gsfc.nasa.gov/telescope/soldering.htm).
	2. Continue by watching some [YouTube Videos](https://www.youtube.com/watch?v=BLfXXRfRIzY&list=PLQ32vZrF5U2lFOJTtZDytBWBYVLNp4RYz).
	3. Be sure to wear safety glasses and consult an expert regarding safety, you can even start at your [local hackerspace](https://wiki.hackerspaces.org/List_of_Hackerspaces).
2. Start by programming the trinket with a blink program prior to soldering to make sure it works.
3. Soldering the headers onto to make sure trinket undamaged.
4. Upload the blink program to the trinket again to make sure it is undamaged.
6, Power the trinket from the power supply. Set the current limit.
4. Test the voltage on the 3.7 V 350 mAh Lithium Ion Polymer 552035 Cell. (Notice from the datasheet that the <a href="https://cdn-shop.adafruit.com/product-files/2750/LP552035_350MAH_3.7V_20150906.pdf">Discharge Cut-off
is 3.0V, the Charging Cut-off is 4.2V, and the Storage Voltage is 3.7-3.85V</a>)
7. Turn on the oscilloscope.
8. Turn on the funtion generator.
9. Disconnect the power supply and connect the 
5. Upload the rover code to the trinket.
6.
7.
8.

Fritzing diagrams needed
![Circuit](raw.githubusercontent.com/six0four/MicroRover/master/images/circuit.jpg)

## 4. Future Development:
- Incorporate multimeter use to check cell.
- Incorporate power supply use as a current controlled alternative to lion cell.
- Incorporate oscilloscope use to view servo motor command signal.
- Incorporate function generator use to create a test control signals.
- Serial communication http://www.ernstc.dk/arduino/tinycom.html to view digitization of infra-red sensor.
- Optimize to stay on desk.
- Optimize to seek dark spaces.
- Optimize for line following.
- Optimize to seek bright spaces and charge via a solar panel.
- Add bluetooth.
- Connect to an Android App that is also connected to Firebase.
- Re-flashing, changing, and removing boot loaders.
- Support for more operating systems.
- Support for more programming languages (Atmel AVR Assembly, ANSI C, Java, Python, IEC 61131-3, javascript, etc.).
- Support for more development environments (AVR-GCC/vi|emacs/AVRdude, Atmel Studio/Visual Studio, etc.).
- Optimize for mapping.
- Communicate with an I2C device as a master
- Communicate with an SPI device.
- Communicate with an I2C device as a slave.
- Communicate with a UART device.
- Communicate via infra-red remote codes.
- Add an H-bridge.
- Add an opto-coupler.
- Add a bidirectional level shifter.
- Modify for DC motors, optical encoders, relays.
- Modify for stepper motors (bipolar and unipolar).
- https://thewanderingengineer.com/2014/08/11/pin-change-interrupts-on-attiny85/
- PID feedback control, fan, thermistor, thermocouple.
- Function generator.
- D to A, PWM.
- A to D, filters.
- Solar cell, photo-resistor.
- Wheatstone bridge, instrumentation amplifier.
- Displays.
- De-bouncing reed switch.
- Emulate a keyboard.
- Playback sound.
- Create a custom PCB with an integrated USB port.
- Shift register, multiplexer.
- RS232, RS485.
- Add a 9-DOF IMU.
- Add MICROCHIP I2C I/O Expander MCP23017.
- Use with http://www.atmel.com/tools/atatmel-ice.aspx and http://www.microchip.com/DevelopmentTools/ProductDetails.aspx?PartNO=ATPOWERDEBUGGER
- Design shell for injection molding.
- Bar/QR code scanners, RFID, magnetic strip, fingerprint readers.
- Add SJA1000/MCP2515 for CAN.
- http://perso.uclouvain.be/fstandae/lightweight_ciphers/
- http://www.instructables.com/id/Optical-Mouse-Odometer-for-Arduino-Robot/?ALLSTEPS
- Currently the project uses a low cost, low power microcontroller from Microchip (Atmel). It could be expanded to be suitable for offerings from other companies such as:
	- Broadcom
	- National Instruments
	- Philips
	- Qualcomm (including NXP, Motorola, and Freescale)
	- Texas Instruments
	- Xilinx
	- Altera
	- Analog Devices
	- Cypress
	- Exynos (Samsung)
	- Infineon Technologies
	- Nordic Semiconductor
	- ON Semiconductor (including Fairchild)
	- Renesas Electronics (including NEC, Hitatchi, Mitsubishi)
	- SGS-THOMSON Microelectronics
	- Silicon Labs

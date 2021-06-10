
# CNC Laser Plotter

## What is a CNC Laser Plotter?


<p align="justify">
CNC stands for computer numerical control. The Arduino CNC laser  plotter moves its parts in accordance with the instructions it is provided in order to draw a desired image or text. It uses 2 stepper motors as actuators and the Arduino controls them individually depending on the instructions it receives.
</p>

## How does a CNC Laser Plotter work?

<br>
<p align= "justify">
A CNC Laser  plotter is able to draw complex line drawings. The coordinates are uploaded to the machine controller by a separate program. The image file is transformed into a G-code via Software. Then the code is transferred to the microcontroller by which the motor mechanism is instructed to draw the image.
</p>

<p align= "justify">
We are going to present a simple design for a CNC laser plotter. Our idea is an Arduino-based design using an ATMEGA328 microcontroller. The machine will have two stepper motors to implement the X ,Y. Drawing will be done on the X-Y plane where the positioning will be controlled by stepper motors.
</p>
<br>

<p align= "center">
  <img src=".\source\images\laser-cnc-plotter-20.png" alt="GESTURES" width=70% hight=50%/>
</p>

## Author
Jerushan Sritharan [Click to see](https://dreamspace.academy/pages/3-2-5-dreambot.php)



### Material List
1. Arduino UNO - 1
2. CNC shield - 1
3. a4988 stepper motor driver - 3
4. mini servo motor -1
5. 12v - 2amps power supply
6. scrap DVD drive - 3
7. some wires for motor connection
8. Nut and bolts.
9. Laser

### Software list
1. Arduino IDE
2. Universal G-code controller
3. Inscape version

### Step - 01

<br>
<p align="justify">
The first step to start building this CNC laser plotter is to disassemble the DVD/cd drives and take off the stepper motors. Use the screwdriver to open and take off the rails.
</p>

<p align="center">
<img src=".\source\images\laser-cnc-plotter-1.jpg" alt="GESTURES" width=70% height=50%/>
</p>

### Step - 02

<br>

In the first image above you will see the Y-axis of our CNC laser plotter. Attach it to your surface, in this part, you will need some screws and nuts.

<p align="justify">
In the second image, you will see the X and Y-axis. The X-axis is attached to two plastic parts that I took from the remaining 'garbage' stuff. I’ve cut it to fit the construction,
this is an easy procedure. Just make sure to put the Y-axis straight to the CNC base and the X-axis vertically in this (90 degrees).
</p>

<p align="center">
<img src=".\source\images\laser-cnc-plotter-13.jpg" alt="GESTURES" width=70% height=50%/>
</p>

### Step - 03
<br>

<p align="justify">
Now that we have our contraction ready, it's time to build the circuit and test stepper motors (X and Y-axis).
Watch the above image with a breadboard circuit schematic.
Stepper motors wiring is something that needs patience. In the next step, you will find a 'testing' code for the x and y-axis.

</p>

<p align="center">
<img src=".\source\images\laser-cnc-plotter-16.png" alt="GESTURES" width=70% height=50%/>
</p>

### Step - 04

<br>

Here is the main CNC laser plotter code embedded using Arduino IDE this part you will see your laser move.

<p align="center">
<img src=".\source\images\laser-cnc-plotter-17.JPG" alt="GESTURES" width=80% height=50%/>
</p>

### Step - 05

<br>

<p align ="justify">
To make G-code files that are compatible with this CNC laser plotter you have to use the Inkscape.
It is used by design professionals and hobbyists worldwide, for creating a wide variety of graphics such as illustrations, icons, logos, diagrams, maps, and web graphics. Inkscape uses the W3C open standard SVG (Scalable Vector Graphics) as its native format and is free and open-source software.
</p>


<p align="center">
<img src=".\source\images\laser-cnc-plotter-18.png" alt="GESTURES" width=80% height=50%/>
</p>

### Step - 06

 Arduino CNC laser plotter machine is completed now we will see the wiring.

 <p align="center">
 <img src=".\source\images\laser-cnc-plotter-3.JPG" alt="GESTURES" width=80% height=50%/>
 </p>

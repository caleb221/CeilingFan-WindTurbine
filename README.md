# CeilingFan-WindTurbine
A Ceiling Fan turned into a Vertical Axis Wind Turbine (VAWT)

# Description
I had come into posession of a trashed ceiling fan, what to do?? <br>
Of course, turn it into a wind turbine!<br>
Here is the result of not having a welder and transforming a solar panel control into a Wind Turbine control.
<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/VAWT_complete1.jpg" alt="lost it somewhere..." width = 400 height=550>
# Schematic
<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/Schematic_wind_power control.png" alt="lost it somewhere..." width = 600 height=400><br>


# Hardware:
Ceiling Fan Motor<br>
Arduino Nano<br>
LM2596S Voltage Regulator package (X2)<br><br>
IRFz44n (X2) <b>OR</b>  IRF9530 (X2) MOSFET Transistor as shown in Schematic<br>
    <code><b>YOUR CHOICE OF MOSFET WILL CHANGE YOUR SCHEMATIC!</b>
    <br>IRFz44n is a <b>N-Channel</b>
    <br>IRF9530 is a <b>P-Channel</b>
  </code>
<br><br>
2004 20X4 LCD Display LCD Screen<br>
pn2222a Transistor (X2) <br>
ACS712 Current Sensors 30Amp (X2)<br>
12V Battery<br>
50V capacitors<br>
10V Zener Diode<br>
20V Zener Diode<br>
1N4007 Diodes<br>
2 Phase Diode bridge Rectefier (X2)<br>
Fuse (5A)<br>
12mm bore Aluminum Shaft <br>
3x12mm Neodyium Magnets (x90)<br>
1/4'' x 2.5'' bolts and nuts <br>
M3 x 12 Screws<br>
Perf boards<br>
Epoxy Glue<br>
Super Glue<br>

# 3D Printer Settings
Printer: Creality Ender 3 pro V2<br>
Filament: Duramic PETG<br>
Infill: 50%<br>
Support: 10% everywhere<br>
Temp: 235<br>
Slicer: Cura --> Slow on the first layer<br>
--> outdoor parts I would reccommend PETG


# Electronics Images
Shown below are the Perf Boards I soldered up to get a working charge controller along with the USB Charger, Battery and 2-Phase bridge rectefier  <br>
The pictures are missing the ACS712 because I had gotten the 5Amp version and attempted to pair it with a 7 Amp battery X(<br>
The Screen is also omitted in order to show the electronics more clearly.<br>
<br>The Bridge Rectefier Diodes are connected to the Turbine via 200+Ft of wires.<br>
<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/electronicsALL2.jpg" alt="lost it somewhere..." width = 400 height=400>

<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/electronicsBatterySide.jpg" alt="lost it somewhere..." width = 300 height=200> This is the side that monitors the Battery

<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/electronics_Transistors2.jpg" alt="lost it somewhere..." width = 300 height=200> This is the MOSFT Control center.


# VAWT STL FILES
The VAWT can be found on Thingiverse at: https://www.thingiverse.com/thing:2284021
# STL / FREECAD FILES
I designed the turbine using FreeCAD, which is free and works on all major OS platforms.<br>
You are free to edit / change all designs, but please give a reference to the original!<br>


ceilingFanRing30 --> This is the main ring which hold the magnets they are superglued in place with poles in correct position. It is bolted onto the metal fan casing in the same way as the original armature.<br>
boltRingSolidBtm --> This is where the 12mm shaft is connected to the outer armature. Each segment in the ring holds 2 1.4'' nuts. There is also one spot for a 1/4'' nut (it is NOT inline with any other) that is meant to act as a set screw.<br> 

boltElbow90 --> 90 Degree interchange for 1/4'' Bolts. Uses nuts to attach, they can be press fit or superglue can be added. <br>
ceilingFanCOVER--> This covers the top portion of the strator.<br>
fanCone1 --> This is the cover for the LOWER half of the armature, I would recommend using the original from the ceiling fan but I threw mine away. <br>

USB Holder --> Holds 5 slots for a USB power rail that is regulated with one LM2596S module set to 5V. This is connected to the LOAD MOSFET of the battery.<br>
USB Cover --> Whats a USB holder without a cover? featuring 2 M3 Screws and My symbol!<br>


** Iterations and design changes were made, but since there aren't any standards for ceiling fans, these might help for attaching bolts**<br>
boltElbow1n1<br>
boltElbowNUTZ<br>
2ndBoltElbow90<br>

# Build Pictures
<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/VAWT_complete2.jpg" alt="lost it somewhere..." width = 400 height=600>
<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/arduinoCtrl1.jpg" alt="lost it somewhere..." width = 400 height=600>

<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/completeTurbine1.jpg" alt="lost it somewhere..." width = 400 height=600>

# Power Electronics
I've been told I'm not Engineering if i dont break something in the process. Here's proof theres actually Engineering going on! <br> Watch those transistor connections!
<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/crispyTransistor.jpg" alt="lost it somewhere..." width = 400 height=600>
<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/turbineBuild2.jpg" alt="lost it somewhere..." width = 400 height=600>
<img src="https://github.com/caleb221/CeilingFan-WindTurbine/blob/main/windTurbineImg/turbineBuild1.jpg" alt="lost it somewhere..." width = 400 height=600>



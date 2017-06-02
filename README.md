# ITSP

# Introduction

The project aims to build an 8*8*8 cube out of LEDs and to control each LED individually using Arduino. The basic idea is to show static or moving patterns on the cube; moving alphabets is one of them. </br>
The cube can be used for 3D plotting,

# Working Principle

Each horizontal layer is to be controlled by Mosfets, and every row of the layers by shift registers. All the 64 pillars of the cube have been designated as the negative terminal for the LEDs to be connected to. Each horizontal row consisting of 8 of such pillars further connects to the corresponding shift register. These 8 shift registers keep shifting the data within one layer.  </br>
The horizontal rows of each layer are shorted, being the positive terminal for the LEDs to be connected to. And each of that horizontal layer is connected to the corresponding mosfet. The continuous switching on and off of the mosfets of every layer displays the pattern on that layer.

# The Code

# Problems faced

The major problems faced were mainly in building the structure and the wiring.
1. Straightening of the wires for the sturdy structure of the cube.
2. Soldering of the LEDs onto these wires.
3. Holding the layers together for the cube to stand straight.
4. The layers getting internally shorted.

# Solutions

1. Initially the drill didnt prove to be useful for the straightening of the wires, as it kept coming ff while it rotated. Afterwards we attached a wooden piece to the drill and entangled the wire through a hole in it, which made the wire hold in place and got us perfectly straightened wires. 

2. The solder used to hold the LEDs kept coming off and hence lost the connection. To tackle this, we took a single strand of a multi-stranded wire and kind of sewed it through all the LEDs, shorting them.

3. A single-stranded wire was used to bind the layers together as well as shorting them.

4. Had to debug each and every layer, and at times each LED too.

# Wiring and Mounting the Flowdeck V2

Skip this step if you do not have a flowdeck or optical flow sensor/rangefinder

1. Find one of your JST GH 6-pin cables as well as an 8 pin dupont header with 6 assorted wires.

Then Cut the 6-pin JST GH cable to be approximately __ mm and remove the insulation from the newly cut end.

<img src="/./Images/Instructions/8_2.jpeg" height="300">

3. Solder 4 of the the wires to the Flowdeck V2 (from the 6-pin JST cable), matching the connections to the two images below. 

Alternatively a header for the Flowdeck could be purchased and the wires soldered to that instead.

The other wires can either be removed from the connector or heat shrink placed over the ends to prevent shorting.

<img src="/./Images/Instructions/I2C.jpg" height="300"> <img src="/./Images/Instructions/flow.jpg" height="300"> 

4. Next solder 6 wires onto the dupont header as shown below and heat shrink over the wires once done.

<img src="/./Images/Instructions/SPI.jpg" height="300">
<img src="/./Images/Instructions/header.jpeg" height="300">

5. Cut the other end of the 6 wires to approximately __ mm, remove the insulation and solder onto the flowdeck according to the diagram below.

NB: Also use another short wire to connect the two power pins as shown by the thicker red wire in image 2.

NB2: The red 3.3V wire connect to the flowdeck and to the telemetry module in a later step (so an additional wire should be soldered). 

<img src="/./Images/Instructions/flow.jpg" height="300">
<img src="/./Images/Instructions/flowdeck.jpeg" height="300">

6. Plug the newly created cables into the ports on the Pixracer, to ensure wire lengths are correct. 

<img src="/./Images/Instructions/9.jpeg" height="300"> <img src="/./Images/Instructions/11.jpeg" height="300">

7. Rotate the frame to be upside down and place clear glue onto the 4 pads indicated below.

<img src="/./Images/Instructions/10.jpeg" height="300">

8. Place the Flowdeck onto the 4 pads, with the arrow facing towards the foreward arrow of the frame and keeping the edge of the flowdeck inline with the edge of the frame carriage.

Hold the Flowdeck in place until it wont slide around anymore. Then let the glue dry...

<img src="/./Images/Instructions/12.jpeg" height="300">

9. Move onto [Replacing the XT60 connectors](./xt30.md)

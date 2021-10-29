# Wiring and Mounting the Flowdeck V2

Skip this step if you do not have a flowdeck or optical flow sensor/rangefinder

1. Rotate the Flowdeck into the orientation shown below.
![](/./Images/frame2pieces.png)
1. Find one of your JST GH 6-pin cables as well as an 8 pin dupont header with 6 assorted wires.
![](/./Images/f41.png)
1. Cut the 6 JST GH cable to be around __ mm and remove the insulation from the newly cut end.
![](/./Images/f41.png)
1. Solder 4 of the the wires to the Flowdeck V2, matching the connections to the two images below. 
Alternatively a header for the Flowdeck could be purchased and the wires soldered to that instead.
The other wires can either be removed from the connector or heat shrink placed over the ends to prevent shorting.
![](/./Images/flow.png)
![](/./Images/I2C.png)
1. Next solder 6 wires onto the dupont header as shown below and heat shrink over the wires once done.
![](/./Images/SPI.png)
![](/./Images/header.png)
1. Cut the other end of the 6 wires to around __ mm, remove the insulation and solder onto the flowdeck according to the diagram below.
NB: Also use another short wire to connect the two power pins as shown by the thicker red wire in image 2.
NB2: The red 3.3V wire doesn't connect to the flowdeck, it connects to the telemetry module in a later step. 
![](/./Images/flow.png)
![](/./Images/flowdeck.png)
1. Plug the cables into the ports shown above on the Pixracer, to ensure wire lengths are correct. 
![](/./Images/f41.png)
1. Rotate the frame to be upside down and place clear glue onto the 4 pads indicated below.
![](/./Images/f41.png)
1. Place the Flowdeck onto the 4 pads, with the arrow facing towards the foreward arrow of the frame and keeping the edge of the flowdeck inline with the edge of the frame carriage.
Hold the Flowdeck in place until it wont slide around anymore. Then let the glue dry...
![](/./Images/flowwithglue.png)
1. Move onto [Replacing the XT60 connectors](./xt30.md)
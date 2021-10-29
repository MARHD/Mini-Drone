# Wiring and Mounting the motors and ESC

1. Simply cut the connectors off of the motor cables and remove a small amount of insulation.
![](/./Images/frame2pieces.png)
1. Straighten the motor wires so that they aren't crossed.
![](/./Images/f41.png)
1. Place the ESC on a flat surface or in helping hands in this orientation.
![](/./Images/f41.png)
1. Solder 5 small wires either onto a connector which fits on the ESC signal header, or directly onto the pads(as I have).
NB: These connectors are tiny so be careful when soldering and moving it around (I would actually recommend a different ESC, mentioned in the BOM file)
![](/./Images/I2C.png)
![](/./Images/I2C.png)
1. Solder the other end of the wires to a 4 way dupont female header and an additional dupont female connector for the GND pin.
The wires should be in order from 1 to 4 on the connector. as indicated on the silk screen of the ESC.
![](/./Images/I2C)
1. Flip the ESC over and solder each of the 3 wires of each motor onto the soldering pads of the ESC, keeping the motor wires completely straight.
![](/./Images/I2C.png)
1. Ensure the middle holes of the motor mounts on the top frame have been deburred as described in: [Printing and Assembling plastic parts](./print_parts.md)
![](/./Images/flowdeck.png)
1. Place padded double sided tape and clear glue in the following pattern on the top frame. 
![](/./Images/f41.png)
1. Place the ESC onto the top of the frame as shown. keeping the edge with power wires flush with the frame and the ESC close but not touching the top left screw holding the Pixracer in.
Hold the ESC in place until it wont move and let the glue dry...
![](/./Images/f41.png)
1. Next place the wires of one motor at the top of the ESC, over the one beside it and the same for the bottom of the ESC, as seen below.
![](/./Images/header.png)
1. Screw the motors in with the provided torx screws(shorter ones), keeping the wires aiming toward the center of the frame. 
![](/./Images/flowwithglue.png)
1. Tuck the excess motor wires into the cut out areas of the top frame.
![](/./Images/I2C.png)
1. Connect the signal wires to the large signal header on the Pixracer as follows, with the GND wire 2 places above the signal wires.
![](/./Images/I2C.png)
1. Move onto [Wiring and Mounting the receiver](./rec.md)
# Wiring and Mounting the Telemetry module

1. Get 5 dupont female wires or a 4x2 dupont female connector and cut the other end of the wires to around __mm.
Also find another 6 pin JST GH cable and cut one end, removing the insulation from both wires.
![](/./Images/frame2pieces.png)
1. Use heat shrink and solder the cables together according to the following diagrams.
NB: the 3.3V wire comes from the SPI header we made before, which connects to the flowdeck.
This 3.3V wire is connected to two places on the telemetry module.
![](/./Images/ESP.png)
![](/./Images/ESPModule.png)
1. Place clear glue onto the area on the top top frame and place the telemetry module on the glue holding until dry.
![](/./Images/f41.png)
1. Plug the 6 pin JST cable into the telemetry 1 port of the Pixracer.
![](/./Images/I2C.png)
1. Move onto [Mounting the battery](./mount_bat.md)
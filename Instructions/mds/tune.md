# Tuning the drone

1. Connect the drone to your laptop via USB, then open your computers wifi networks and connect to ArduPilot or PixRacer with the password "ardupilot" or "pixracer" respectively.
![](/./Images/f41.png)
1. Next in Mission Planner change the connection type from COM to UDP and click connect. Click ok for the default port number.
You should now be connected via the Wifi telemetry to Mission Planner (powered via USB).
![](/./Images/f41.png)
1. To fly the drone, I would first plug in via USB, connect to the wifi and mission planner, 
then plug in the battery, unplug the usb cable and turn on the transmitter. This is to save battery life, as connecting is not always quick.
1. Follow the instructions on the ArduPilot tuning [page](https://ardupilot.org/copter/docs/tuning-process-instructions.html\) to get you through your first flight and rough tune (skip to "Pilot’s preparation for first flight" on the page).
Although with the paramter file having being uploaded, the drone should have enough of a tune to be able to at least hover in stabilize mode.
![](/./Images/frame2pieces.png)
1. Once comfortable flying the drone, move to a large open space or outside on a still day and proceed to following the instructions for AutoTuning the drone, [here](https://ardupilot.org/copter/docs/autotune.html)
![](/./Images/f41.png)
1. After doing an autotune proceed to tune the optical flow sensor according to ArduPilots [page](https://ardupilot.org/copter/docs/common-optical-flow-sensor-setup.html).
1. Most of the settings should already be inputted for the last 3 steps, but the tuning will be different for every craft.
![](/./Images/flow.png)
1. To use Loiter mode without a GPS(uses optical flow and rangefinder), you need to "Set EKF home here" in Mission Planner by right clicking on the map. 
1. Happy Flying.






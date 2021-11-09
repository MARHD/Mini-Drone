# Tuning the drone

1. Connect the drone to your laptop via USB, then open your computers wifi networks and connect to ArduPilot or PixRacer with the password "ardupilot" or "pixracer" respectively.

<img src="/./Images/Instructions/wifi.png" height="300">

2. Next in Mission Planner change the connection type from COM to UDP and click connect. Click ok for the default port number.

You should now be connected via the Wifi telemetry to Mission Planner (powered via USB)

<img src="/./Images/Instructions/udp.png" height="300"> <img src="/./Images/Instructions/port.png" height="300">

3. To fly the drone, I would first plug in via USB, connect to the wifi and mission planner, then plug in the battery, unplug the usb cable and turn on the transmitter. This is to save battery life, as connecting is not always quick.

4. Follow the instructions on the ArduPilot tuning [page](https://ardupilot.org/copter/docs/tuning-process-instructions.html) to get you through your first flight and rough tune (skip to "Pilot’s preparation for first flight" on the page).

Although with the paramter file having being uploaded, the drone should have enough of a tune to be able to at least hover in stabilize mode.

<img src="/./Images/Instructions/first.png" height="300">

5. Once comfortable flying the drone, move to a large open space or outside on a still day and proceed to following the instructions for AutoTuning the drone, [here](https://ardupilot.org/copter/docs/autotune.html)

<img src="/./Images/Instructions/autotune.png" height="300">

6. After doing an autotune proceed to tune the optical flow sensor according to ArduPilots [page](https://ardupilot.org/copter/docs/common-optical-flow-sensor-setup.html).

Most of the settings should already be inputted for the last 3 steps, but the exact tuning will be different for every drone.

8. To use Loiter mode without a GPS (uses optical flow and rangefinder), you need to "Set EKF home here" in Mission Planner by right clicking on the map. 

<img src="/./Images/Instructions/home.png" height="300">

9. Happy Flying.







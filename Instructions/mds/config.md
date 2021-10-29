# Configuring ArduPilot

1. Download the latest "main" parameter file [here](/./Software/ArduCopter-4.1%20Custom/Mission%20Planner%20Parameters/)
1. With the drone connected via USB, click the "config" button at the top of Mission Planner, followed by the "full parameter list" tab.
![](/./Images/config.png)
![](/./Images/param.png)
1. Click on the "Load from file" button on the right hand side and navigate to where you saved the parameter file earlier.
Choose the file and click open.
The parameter list should be updated
![](/./Images/f41.png)
1. Click on the "Write Params" button on the right, to save these parameters ontp the drone.
Once completed, restart the drone by unplugging and plugging the USB back in.
![](/./Images/f41.png)
1. Click on the "Setup button" again, at the top of Mission Planner. Then click on the "Mandatory Hardware" tab. 
Go through each of the sub categories of "Mandatory Hardware" to calibrate the Accelerometers, Gyroscope and compass as well as setting up the transmitter,
according to the [ardupilot setup page](https://ardupilot.org/copter/docs/configuring-hardware.html)
![](/./Images/flow.png)
1. Move onto [Installing propellers](./props.md)
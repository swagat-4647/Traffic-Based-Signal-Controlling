# Traffic-Based-Signal-Controlling
## Embedded System Project for B.Tech Semester 1 
For Semester 1, I worked on a project named Traffic Based Signal Controlling which was a typical Embedded System based project where I implemented smart signals, 
which were able to reconfigure there open and close time depending on the traffic sensed for the particular end of intersection.
To sense the traffic IR sensors were used and a base level prototype was demonstrated.
Each intersection has 3 IR sensors set at different distance from intersection indicating the traffic density as Low, Moderate and High.
If low Traffic was sensed the channel was reconfigured to minimum open time, and maximum open time if high traffic density was sensed 
without affecting open/close time for other channels. 
Prototype was desgined using STM32 make development board: STM32-NUCLEO F446RE. 
Markup :  - - - -
Below given image shows the flow of system.
![image](https://user-images.githubusercontent.com/81175552/167254011-c4058d38-508a-4bcf-9dd3-26b663c28e27.png)
Markup :  - - - -
Here is the Circuit Diagram of project.
![image](https://user-images.githubusercontent.com/81175552/167254057-87c90cda-78e9-47f0-b9c6-60556eedf69c.png)
Markup :  - - - -
Components Used:
Markup: 1. Development Board - STM32 Nucleo F446RE (Any other development Board with sufficient Digital GPIO pins will work)
2. Sensor - OEM IR sensor module
3. Traffic Light - OEM 3 led module.

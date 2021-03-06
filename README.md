# Mobile-Robot-Simulator

Through this installer it is possible to acquire a simulation software for mobile robotic systems. With this it is possible to test and validate the performance of the strategy created by me for the Worldskills Shanghai competition. 
For more information about the software you can see some videos on my Youtube channel (https://www.youtube.com/channel/UCVb2UyDGOf5kojiQygPRMbQ), in which it is shown how to use it, and each video has a complete text in the description explaining how the tool works.

To install the simulator it is necessary to use the Package Manager provided by National Instruments (https://www.ni.com/pt-br/support/downloads/software-products/download.package-manager.html#322516)

The image below shows the interface where all infos are. There are a lot of visual resources to better show the simulated robot, you can see the robot movement around hospital, the object manipulator system and some velocity graphs. 
![image](https://user-images.githubusercontent.com/103584400/164027521-15b09444-1c7f-44c9-80e4-89d6cf3c83a4.png)
On the right side you can see a Tab Control. The Layout tab that is being shown is used to place the coordinates of all objects (walls, gurneys, dispensary, pads and stands), which is necessary for the robot to know the Hospital environment. With these infos it is possible to determine all the movements necessary to complete the tasks.

The Evaluation tab is used to enter the Work Order Chart and the initial state of the Dispensary. This information will be used when running the simulation in Evaluation mode. An example using this tool can be seen here: https://youtu.be/bnKrGPTR3d0

![image](https://user-images.githubusercontent.com/103584400/164044568-228fe85c-7444-4f49-acde-df7511a03e98.png)

The Simulation tab is used to control some simulation parameters and is also used to show objects in rooms. These controls helps to set on the better way your simulationg, for example, you can turn off the OMS simulation so you can only see the robot's movement and the robot decision making. This tab is also used to insert the initial and final point to Movement simulation mode. (https://youtu.be/n-ZOoRrbey0)

![image](https://user-images.githubusercontent.com/103584400/164045792-463c9047-a0e4-455c-9944-290625d2d10d.png)

The last tab is intended to simulate a position correction using a distance sensor. To do that it is necessary to insert the sensor position according to the robot's center. With this strategy it is possible to determine the robot position with any distance sensor without needing to manual insert the wall position, the software calculates by eachself which wall it is being used by the sensor. (https://youtu.be/y4DUthScQ9Y)

![image](https://user-images.githubusercontent.com/103584400/164049132-5709d7e9-d0bb-46a2-9748-8035b582da16.png)

## ROS and experimental robotics
  The Robot Operating System (ROS) is a set of software libraries and tools that help you build robot application. In our case, we modelized the navigation of a turtlebot burger to navigate through various pathways with Gazebo and RViz.
  
![turtlebot_path](https://github.com/Miightx/turtlebot_burger-navigation/assets/117952621/d6ba08c4-175b-4637-b4cd-12ea9a7457d1)

Therefore, we faced three challenge: 
- Line following (utilizing OpenCV with the robot's camera)
- Navigation through a corridor (exploiting LDS data)
- Navigation in a cluttered environment (both LDS data and camera) until the exit

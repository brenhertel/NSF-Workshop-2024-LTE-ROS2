# NSF-Workshop-2024-LTE-ROS2

Instructions for demo:
1. Install ROS2 Humble. Follow the instructions here: https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html
2. Install Gazebo for ROS2 Humble. Follow the instructions here: https://github.com/gazebosim/ros_gz/tree/humble
3. Install the UR ROS2 driver. Follow the instructions here: https://github.com/UniversalRobots/Universal_Robots_ROS2_Driver/tree/humble?tab=readme-ov-file
4. Install the UR ROS2 driver gazebo simulator. Follow the instructions here: https://github.com/UniversalRobots/Universal_Robots_ROS2_Gazebo_Simulation/tree/humble Note: If you have trouble with the `colcon build` command follow the first set of instructions here: https://github.com/ros-industrial/industrial_ci/issues/646
5. Source the terminal to the local workspace using `source install/setup/bash`
6. The previous install included setting up a workspace. In that workspace, download the file `lte_sim_demo.py`.

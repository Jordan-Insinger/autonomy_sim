# Aero Common
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)

Common package containing all required ROS2 packages to run a single agent at the autonomy park.

<img alt="Awesome GitHub Profile Readme" src="docs/trajectory_tracking.gif"> </img>


## Packages

| Name | Description |
|---|---|
   | autonomy_park_viz | RViz2 visualization with park geometry. |
   | minimal_startup_air | Contains launch files and startup scripts for sim + physical experiments. |
   | px4_safety_lib | Potential field based safety library for perimeter and obstacle avoidance. |
   | px4_telemetry | Handles telemetry data and frame transformations from ENU to Autonomy Park. |
   | px4_teleop | Teleoperation node. |
   | swarm_interfaces | Library with msgs + srvs used for experiments. |

## Note on Submodules

Submodules will be empty after cloning repo, to update them run:
```bash
git submodule update --init --recursive
```

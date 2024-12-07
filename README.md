# Robotic-ARM-Manipulator-assigned-to-do-Pick-Place-task

![Robotic ARM Simulation](https://github.com/Arosh-Upathilak/Robotic-ARM-Manipulator-assigned-to-do-Pick-Place-task/blob/main/Robodk.png)

## Description
This project automates the **Pick & Place** task as part of a manufacturing process using a robotic arm (manipulator). The robotic system is simulated using **RoboDK** and analyzed with **MATLAB** (Robotics Toolbox) to verify trajectory planning and generate velocity profiles. The task involves:

- Picking a disk from **Station 1** (via conveyor).
- Placing it in **Station 2** for labeling.
- Moving it to **Station 3** for transfer to another conveyor.

### Disk Specifications
- **Width**: 2 cm
- **Weight**: 0.5 kg

## Key Features

### Robotic Arm Selection
The manipulator is chosen based on:
- **Degrees of Freedom**
- **Reach (Workspace)**
- **Payload Capacity**

### Trajectory Planning
- Waypoints are defined between pick and place points.
- Both **Forward Kinematics** and **Inverse Kinematics** are implemented.
- Simulation ensures smooth transitions using two waypoints.

### Simulation Tools
1. **RoboDK**: For modeling and simulating the robotic arm in a realistic environment.
2. **MATLAB**: To generate velocity profiles, and verify kinematics (with/without the Robotics Toolbox).

## Deliverables
- **Simulation Snapshots**: Demonstrates tuning and testing of tasks.
- **Kinematics Analysis**: Includes velocity profiles, forward, and inverse kinematics.
- **Comprehensive Report**: Detailed task description, strategic plan, and results.

## How to Run
1. Download the robotic arm simulation model from the RoboDK library.
2. Configure the trajectory waypoints in RoboDK.
3. Use MATLAB to analyze the kinematics and validate the simulation results.
4. Follow the task sequence as per project description.

## Contact
For queries or contributions:

📧 aroshupathilak@gmail.com

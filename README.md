# ROSCon 2022 workshop on ros2_control

Thank you for your interest in ros2_control.
This repository is developed with a purpose of supporting workshop on *ros2_control* @ ROSCon2022 in Kyoto, Japan.
Regardless if you could or could not participate the repository will provide you with detailed instruction on how utilize *ros2_control* framework and explain functionality and purpose of its individual parts.


## What is *ros2_control*

Simply, ros2_control is a control framework for ROS2.
But actually, it is much more, it is kernel of ROS2 system that controls robots:
 - it abstracts hardware and low-level control for other framework like MoveIt2 and Nav2;
 - it provide resource access management,
 - controls theirs lifecycle and so on.


For more details check [this presentation]


## Structure of this repository (and workshop)

The structure of the repository follows the flow of integrating robots with ROS2 and those are the following steps:

1. 📑 Setting up hardware description for *ros2_control*

   1. 🗒 Setting up URDF using XACRO for a robot
   2. 📝 Extending robot's URDF with `<ros2_control>` tag

2. 🖥 Using *Mock Hardware* plugin for simple and generic testing of the setup (and how it can save you ton of time and nerves )

   1. 🛠 How to setup *Mock Hardware* for a robot?
   2. 🔩 How to test it with a of-the-shelf controller?

3. ⚙ Getting know the roles of the main components of *ros2_control* framework: *Controller Manager*, *Controllers*, *Resource Manager* and *Hardware Interface*

4. 🔃 Getting familiar with the lifecycle of controllers and hardware and how to use it

5. 🤖 How to write a hardware interface for a robot

6. 💻 Simulating your hardware using Gazebo Classic and Gazebo

7. 🛂 How to write a controller

8. 🔗 Reusing standard controller and creating controller-chains

9. ♻ Modular reuse of hardware drivers for complex systems

10. 🤖🤖🤖 Managing multiple robots with ros2_control

11. 🔬 Introspection of *ros2_control* system

12. 👑 King's Tips:

   1. 💉 Parameter injection
   2. ⚖ Typical setup of robots and it packages


## Hardware used in this repository

The repository uses **Hercules** robot...


## 💻 Simulating your hardware using Gazebo Classic and Gazebo

**Branch**: 6-simulating-hardware

#### Gazebo Classic

You have to add `gazebo_ros2_control` plugin in your robot's URDF, e.g.,

```

```














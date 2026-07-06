<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:0f172a,50:2563eb,100:14b8a6&text=JiaVerso&fontColor=ffffff&fontSize=46&fontAlignY=38&desc=Autonomous%20Navigation%20Robot%20%7C%20ROS%202%20%7C%20SLAM%20%7C%20UAV%20Systems&descAlignY=60&descSize=16" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2600&pause=900&color=38BDF8&center=true&vCenter=true&width=760&lines=Building+robots+that+sense%2C+map%2C+navigate+and+act.;ROS+2+autonomous+navigation+%2B+LiDAR+SLAM+%2B+embedded+control.;From+real+sensors+to+real+field+tests.)](https://git.io/typing-svg)

[![GitHub](https://img.shields.io/badge/GitHub-JiaVerso-181717?style=flat-square&logo=github)](https://github.com/JiaVerso)
[![ROS2](https://img.shields.io/badge/ROS%202-Humble-22314E?style=flat-square&logo=ros)](https://docs.ros.org/en/humble/)
[![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus)]()
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)]()
[![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics)]()
[![Livox](https://img.shields.io/badge/Livox-MID360-00A3E0?style=flat-square)]()

</div>

---

## Hi, I'm JiaVerso

I focus on robotics software, autonomous navigation, SLAM, embedded control, and UAV ground station development.

Currently building **SparkCar_ROS2_WS**, an autonomous navigation robot workspace based on ROS 2, Livox MID360, FAST-LIO2, Nav2, Hunter SE chassis control, and mapping/localization tools.

---

## Main Project

<div align="center">

<a href="https://github.com/JiaVerso/SparkCar_ROS2_WS">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=JiaVerso&repo=SparkCar_ROS2_WS&theme=github_dark&hide_border=true" />
</a>

</div>

### SparkCar_ROS2_WS

<table>
<tr>
<td width="58%">

**SparkCar_ROS2_WS** is my autonomous navigation robot workspace.

It integrates:

- Hunter SE / Ackermann chassis driver
- Livox MID360 LiDAR driver
- FAST-LIO2 localization and mapping
- PGO map optimization workflow
- Nav2 global planning and local control
- PCD to PGM map conversion
- ROS 2 launch scripts for real robot testing

</td>
<td width="42%">

```text
SparkCar_ROS2_WS
├─ HunterSE_Driver
│  ├─ hunter_base
│  ├─ hunter_msgs
│  └─ ugv_sdk
├─ SparkCar_Perception
│  ├─ livox_ros_driver2
│  ├─ fastlio2
│  ├─ localizer
│  └─ pgo
├─ SparkCar_Navigation
│  ├─ sparkcar_nav_bringup
│  └─ hybrid_astar_planner
└─ SparkCar_Tools
   └─ pcd2pgm

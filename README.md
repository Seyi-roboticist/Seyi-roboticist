<div align="center">

<!-- TYPING SVG HEADER -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=64B5F6&center=true&vCenter=true&multiline=true&width=700&height=80&lines=Oluwaseyi+%22Seyi%22+Afolayan;Controls+%E2%80%A2+Manipulation+%E2%80%A2+Flight+%E2%80%A2+Autonomy)](https://seyi-roboticist.github.io)

<br>

<a href="https://seyi-roboticist.github.io"><img src="https://img.shields.io/badge/portfolio-seyi--roboticist.github.io-0f1923?style=for-the-badge&logo=github&logoColor=64b5f6" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/oluwaseyi-r-afolayan-4b8330206/"><img src="https://img.shields.io/badge/LinkedIn-Seyi_Afolayan-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:seyirafolayan@gmail.com"><img src="https://img.shields.io/badge/Gmail-seyirafolayan-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

---

### `> whoami`

Controls Engineer at **The RDI Group** designing industrial automation systems. **MSE Robotics** from Johns Hopkins (LCSR, Distinguished Fellowship, Prof. Whitcomb's lab). **BSc.Eng Mechatronics** from UPEI — first in class, 4.1/4.3 GPA. I build real-time systems that make robots manipulate, navigate, and fly.

```yaml
location:  Illinois, US
education: Johns Hopkins University (MSE Robotics) · UPEI (BSc.Eng Mechatronics)
focus:     real-time control · manipulation · flight dynamics · autonomy
licenses:  FAA & Transport Canada Remote Pilot
```

---

### `> ls ~/expertise`

<table><tr><td valign="top" width="50%">
<h4>🦾 Manipulation & Controls</h4>
<p>Real-time Cartesian control on UR5/UR5e. SVD-based damped pseudo-inverse Jacobian IK with PID + anti-windup at <b>500Hz</b>. Sub-millimeter tracking accuracy.</p>
<h4>🛩️ Flight Controls & GNC</h4>
<p>6DOF modeling, successive loop closure, dual EKF state estimation. Autopilot design from first principles for fixed-wing & multirotor platforms.</p>
</td><td valign="top" width="50%">
<h4>👁️ Perception & Deep Learning</h4>
<p>NeRF for 3D reconstruction, computer vision pipelines, sim-to-real transfer. Custom training with positional encoding.</p>
<h4>🤖 Autonomy & Industrial</h4>
<p>Full-stack ROS 2 autonomy from sim to hardware. Allen-Bradley PLC programming, ladder logic. Bridging modern robotics with legacy controls.</p>
</td></tr></table>

---

### `> cat tech_stack.yml`

<div align="center">

**`Languages`**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

**`Robotics & Controls`**

![ROS2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6600?style=for-the-badge&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

**`Infrastructure`**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**`Hardware`**

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![NVIDIA](https://img.shields.io/badge/Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

</div>

---

### `> cat featured_projects.md`

<table><tr><td width="50%">
<h4 align="center">🎯 Real-Time Cartesian Controller</h4>
<p align="center">
<a href="https://github.com/Seyi-roboticist/_controller_"><img src="https://img.shields.io/badge/Repo-0f1923?style=flat-square&logo=github&logoColor=64b5f6"/></a>
<a href="https://www.youtube.com/watch?v=lPNE6-0R59k"><img src="https://img.shields.io/badge/Demo-FF0000?style=flat-square&logo=youtube&logoColor=white"/></a>
<a href="https://seyi-roboticist.github.io/projects/cartesian-controller/"><img src="https://img.shields.io/badge/Write--up-64b5f6?style=flat-square&logo=googlechrome&logoColor=0f1923"/></a>
</p>
<p>SVD-based damped pseudo-inverse Jacobian IK with Tikhonov regularization. Three ROS 2 packages: sensor driver, controller plugin, launch/config. <b>±0.7mm @ 500Hz</b> on UR5/UR5e hardware.</p>
<p><code>C++</code> <code>ROS 2</code> <code>KDL</code> <code>Eigen</code> <code>ros2_control</code></p>
</td><td width="50%">
<h4 align="center">🛩️ 6DOF Flight Dynamics & Autopilot</h4>
<p align="center">
<a href="https://seyi-roboticist.github.io/projects/flight-dynamics/"><img src="https://img.shields.io/badge/Write--up-64b5f6?style=flat-square&logo=googlechrome&logoColor=0f1923"/></a>
</p>
<p>Nonlinear 6DOF aircraft simulation with trim analysis, successive loop closure autopilot, stability margin verification, and dual EKF state estimation.</p>
<p><code>MATLAB</code> <code>Simulink</code> <code>Control Theory</code> <code>EKF</code></p>
</td></tr><tr><td width="50%">
<h4 align="center">🚁 Aurelia X4 UAV Autonomy</h4>
<p align="center">
<a href="https://seyi-roboticist.github.io/projects/aurelia-uav/"><img src="https://img.shields.io/badge/Write--up-64b5f6?style=flat-square&logo=googlechrome&logoColor=0f1923"/></a>
</p>
<p>Full autonomous flight stack: MAVROS integration, waypoint navigation, obstacle avoidance on NVIDIA Jetson. Team lead & FAA-licensed Remote PIC.</p>
<p><code>ROS 2</code> <code>MAVROS</code> <code>PX4</code> <code>Gazebo</code> <code>Jetson</code></p>
</td><td width="50%">
<h4 align="center">🧠 NeRF 3D Reconstruction</h4>
<p align="center">
<a href="https://seyi-roboticist.github.io/projects/nerf/"><img src="https://img.shields.io/badge/Write--up-64b5f6?style=flat-square&logo=googlechrome&logoColor=0f1923"/></a>
</p>
<p>Neural radiance fields for novel view synthesis. Custom training pipeline with positional encoding and volumetric rendering.</p>
<p><code>PyTorch</code> <code>Python</code> <code>CUDA</code> <code>Deep Learning</code></p>
</td></tr></table>

<p align="center">
<a href="https://seyi-roboticist.github.io">
<img src="https://img.shields.io/badge/→_All_Projects-64b5f6?style=for-the-badge&logo=googlechrome&logoColor=0f1923"/>
</a>
</p>

---

### `> git log --oneline`

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=Seyi-roboticist&show_icons=true&hide_border=true&bg_color=0f1923&title_color=64b5f6&icon_color=64b5f6&text_color=b3d9f2&ring_color=64b5f6" width="48%" alt="GitHub Stats"/>
<img src="https://streak-stats.demolab.com?user=Seyi-roboticist&hide_border=true&background=0f1923&stroke=2a4a6a&ring=64b5f6&fire=f97316&currStreakLabel=64b5f6&sideLabels=b3d9f2&currStreakNum=e3f2fd&sideNums=e3f2fd&dates=6a9ec0" width="48%" alt="GitHub Streak"/>
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Seyi-roboticist&layout=compact&hide_border=true&bg_color=0f1923&title_color=64b5f6&text_color=b3d9f2&langs_count=8" width="40%" alt="Top Languages"/>
</p>

---

### `> cat education.log`

```
┌──────────────────────┬──────────────────────────────────────┬─────────┐
│  MSE Robotics        │ Johns Hopkins University (LCSR)      │ 2025    │
│                      │ Distinguished Robotics Fellowship     │         │
│                      │ Prof. Louis Whitcomb's Lab (IEEE Fel.)│         │
├──────────────────────┼──────────────────────────────────────┼─────────┤
│  BSc.Eng Mechatronics│ University of Prince Edward Island    │ 2023    │
│                      │ First in Class · 4.1/4.3 GPA         │         │
│                      │ Summa Cum Laude                       │         │
└──────────────────────┴──────────────────────────────────────┴─────────┘
```

`800+` students mentored as TA across four graduate robotics courses at Hopkins. SpudNik-1 CubeSat with the Canadian Space Agency. Dual FAA & Transport Canada remote pilot licenses.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=64b5f6&height=80&section=footer"/>

**I build robots that work in the real world.**

[![Portfolio](https://img.shields.io/badge/seyi--roboticist.github.io-→-64b5f6?style=flat-square&logo=googlechrome&logoColor=white)](https://seyi-roboticist.github.io)

</div>

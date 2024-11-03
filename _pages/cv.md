---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Robotics, Johns Hopkins University, 2023
* M.Eng. in Mechanical Engineering, Rensselaer Polytechnic Institute, 2021
* B.S. in Aeronautical and Mechanical Engineering, Rensselaer Polytechnic Institute, 2020

Work Experience
======
* July 2023 - now: Staff Engineer
  * Nautilus X-Ray
  * Completed Projects:
    * Innovated a magnetic field mapping system (Cartesian Robot) to validate the electron steering system on Mach-2. Developed an efficient method to accurately map magnetic fields, ensuring optimal performance of the electron steering mechanism.
    * Developed a real-time pressure and temperature monitoring system designed for Drift Tube Testing within the High Vacuum Condition Chamber.
  * Supervisor: Andrew Cross

Research Experience
======
* Jul 2021 - May 2023: Research Assistant
  * Johns Hopkins University
  * Completed Projects:
     * Designed and conducted a comparative study between two cooperative-control robots by analyzing the user's hand-to-tool interaction force/torque and the robot's tool-to-eye interaction force based on learning curve theory and cumulative sum chart.
     * Installed and tested a fiber bragg grating (FBG) force sensing tool on the end effector of a new eye surgical robot - the Steady-Hand Eye Robot (SHER-3.0) for measuring the tool-to-eye interaction forces for vitreoretinal surgery.
     * Implemented a low pass filter to reduce noise in the force/torque sensor measurements for a cooperative eye surgical robot. This filter allows for tremor-free manipulation during surgery.
     * Implemented a virtual remote center of motion (V-RCM) control algorithm for the SHER-3.0 in C++.
     * Using Bernstein polynomial approximation, fixed a gravity compensation issue that could cause abnormal behaviors of the end effector for the SHER-3.0.
     * Independently designed a 5-DOF counterweight passive positioning arm for the SHER-3.0 with SolidWorks and built a fully functional prototype with standard parts purchased from McMaster-Carr for testing.
  * Supervisor: Prof. Iulian Iordachita

* Sep 2020 - May 2021: Research Assistant
  * Rensselaer Polytechnic Institute
  * Completed Projects: 
     * Set and developed a rapid process of reverse engineering with FaroArm and SolidWorks to analyze and compare the margin of error between the CAD models and the real manufactured parts. 
     * Performed image processing for edge detection and modeling fabric alignment on complex surfaces of metallic machine components.
  * Supervisor: Glenn Saunders, Prof. Daniel Walczyk
  
Skills
======
* CAD/FEA/CFD: SolidWorks, Siemens NX, Solid Edge
* Programming: MATLAB, Python, C, C++
* Technologies: ROS, Linux, Arduino, Simulink, Latex
* Languages: Chinese, English

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

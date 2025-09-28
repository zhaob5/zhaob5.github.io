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

Research Experience
======
* Jul 2021 - May 2023: Research Assistant
  * Johns Hopkins University
  * Completed Projects:
     * Derived the forward and inverse kinematics, Jacobian and Jacobian pseudo-inverse for SHER-3.0, a 5-DOF hybrid Delta-Serial cooperative robot designed for eye surgery. Published the full derivation and validation on GitHub: https://github.com/zhaob5/sher3-kinematics
     * Integrated an ATI Nano17 force/torque sensor into the robot’s end effector for capturing surgeon's hand-to-tool interaction force/torque, enabling synergistic motion in admittance control mode.
     * Developed a simplified Virtual Remote Center of Motion (V-RCM) control method with admittance control mode in C++, allowing the user to set the center of rotation at any desired location on the sclera.
     * Tested an FBG-based force sensor embedded in SHER-3.0’s tool shaft to measure tool-to-trocar interaction force, supporting a control strategy aimed at minimizing contact force for safer vitreoretinal surgery.
     * Designed and built a passive counterbalance articulating arm to enhance SHER-3.0's positioning flexibility, making the system easier to deploy in different testing scenarios.
     * Applied Bernstein polynomial approximation for precise gravity compensation, preventing unintended tool movement caused by gravitational forces in admittance control mode.
     * Designed and conducted a comparative study between two different cooperative-control robots by analyzing the surgeon's applied force and the robot's tool-to-eyeball interaction force, with learning curve theory and cumulative sum chart for performance evaluation.
  * Supervisor: Iulian Iordachita

* Sep 2020 - May 2021: Research Assistant
  * Rensselaer Polytechnic Institute
  * Completed Projects: 
     * Performed image processing for edge detection and fabric alignment analysis on carbon fiber layers bonded to metal parts to assess the quality of robotic Fabric-to-Metal adhesion. Conducted a comparative study evaluating two different end effectors: kinematic roller and granular jamming.
     * Developed a rapid performance evaluation process using FaroArm and SolidWorks to compare the margin of error between CAD models and real Robotic Fabric-to-Metal adhesive parts. Optimized inspection workflow, reduced average evaluation time from 47 minutes to 32 minutes.
  * Supervisor: Glenn Saunders, Daniel Walczyk

<!--Work Experience
======
* July 2023 - now: Staff Engineer
  * Nautilus X-Ray
  * Completed Projects:
    * Innovated a magnetic field mapping system (Cartesian Robot) to validate the electron steering system on Mach-2. Developed an efficient method to accurately map magnetic fields, ensuring optimal performance of the electron steering mechanism.
    * Developed a real-time pressure and temperature monitoring system designed for Drift Tube Testing within the High Vacuum Condition Chamber.
  * Supervisor: Andrew Cross-->
  
Skills
======
* CAD/FEA/CFD: SolidWorks, SolidWorks Simulation, Siemens NX, NX Design Simulation, Solid Edge
* Programming: MATLAB, Python, C/C++
* Technologies: ROS, Linux, Arduino, Simulink, Latex
* Languages: Chinese, English

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

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
* B.S. in Aeronautical Engineering & Mechanical Engineering, Rensselaer Polytechnic Institute, 2020

Research Experience
======
* Jul 2021 - May 2023: Research Assistant
  * Johns Hopkins University
  * Advisor: Iulian Iordachita
  * Completed Projects:
     * Derived the forward and inverse kinematics, Jacobian and Jacobian pseudo-inverse for SHER-3.0, a 5-DOF hybrid Delta-Serial cooperative robot designed for eye surgery. Published the full derivation and validation on GitHub: https://github.com/zhaob5/sher3-kinematics
     * Integrated an ATI Nano17 force/torque sensor into the robot’s end effector for capturing surgeon's hand-to-tool interaction force/torque, enabling synergistic motion in admittance control mode.
     * Developed a simplified Virtual Remote Center of Motion (V-RCM) control method with admittance control mode in C++, allowing the user to set the center of rotation at any desired location on the sclera.
     * Tested an FBG-based force sensor embedded in SHER-3.0’s tool shaft to measure tool-to-trocar interaction force, supporting a control strategy aimed at minimizing contact force for safer vitreoretinal surgery.
     * Designed and built a passive counterbalance articulating arm to enhance SHER-3.0's positioning flexibility, making the system easier to deploy in different testing scenarios.
     * Applied Bernstein polynomial approximation for precise gravity compensation, preventing unintended tool movement caused by gravitational forces in admittance control mode.
     * Designed and conducted a comparative study between two different cooperative-control robots by analyzing the surgeon's applied force and the robot's tool-to-eyeball interaction force, with learning curve theory and cumulative sum chart for performance evaluation.

* Sep 2020 - May 2021: Research Assistant
  * Rensselaer Polytechnic Institute
  * Advisor: Glenn Saunders, Daniel Walczyk
  * Completed Projects: 
     * Performed image processing for edge detection and fabric alignment analysis on carbon fiber layers bonded to metal parts to assess the quality of robotic Fabric-to-Metal adhesion. Conducted a comparative study evaluating two different end effectors: kinematic roller and granular jamming.
     * Developed a rapid performance evaluation process using FaroArm and SolidWorks to compare the margin of error between CAD models and real Robotic Fabric-to-Metal adhesive parts. Optimized inspection workflow, reduced average evaluation time from 47 minutes to 32 minutes.

Work Experience
======
* July 2023 - now: Staff Engineer
  * Nautilus X-Ray
  * Completed Projects:
    * Designed and built a rotary feedthrough for ultra-high vacuum systems, enabling motion transmission across vacuum boundaries with a bellows–sealed interface, maintaining pressure integrity down to 10E-11 Torr.
    * Designed and prototyped a 3-DOF Cartesian platform as an automatic magnetic field mapping system with a workspace of 500 x 400 x 250 mm. Powered by NEMA23 and NEMA17 stepper motors with lead-screw-driven linear stage, GT2 timing pulleys and belts.
    * Integrated a SENIS F3A Hall probe with a 3D printed end effector to measure and plot magnetic field vectors in Gauss along desired trajectories, enabling detailed characterization of magnetic field distributions.
    * Developed a Python-based control system to interface with the motion controller and Hall probe, with GRBL firmware and SCPI protocol for motion control and data acquisition.
    * Collaborated with a multidisciplinary engineering team to develop a lightweight and compact rotating gantry for the Electron Beam Cardiac CT prototype, Mach-3.5. Using air bearings to support a 360 kg gantry that can rotate up to 300 RPM, driven by Kollmorgen AKM servo motor and AKD motor drive.
    * Designed the pneumatic line routing for air bearings, integrated line routing on the stationary frame to deliver filtered air (ISO 8573 standard) at desired pressure and flow rate to radial and thrust bearings.
    * Designed a Modular Detector Rail Assembly using SolidWorks with ISO 2768 standard to hold and align X-ray detectors around the rotating gantry. Performed FEA and topology optimization using SolidWorks Simulation, reducing weight by 16% while maintaining radial deflection under 0.25 mm at 300 RPM.

  
Skills
======
* CAD/FEA/CFD: SolidWorks, SolidWorks Simulation, Siemens NX, NX Design Simulation, Solid Edge
* Document Management: SolidWorks PDM, GitHub, DokuWiki
* Manufacturing & Prototyping: CNC Machining, Sheet Metal Forming, 3D Printing (DFM, MJF)
* Technical Standards: ASME Y14.5 (GD&T), ISO 2768, ISO 1940, ISO 8573, ISO 13485, LaTeX
* Programming: MATLAB, Python, C/C++
* Motion Control & Robotics: Stepper/Servo Motors, Forward/Inverse Kinematics, Admittance Control, RCM, Kalman Filter, Haptic Feedback, ROS

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

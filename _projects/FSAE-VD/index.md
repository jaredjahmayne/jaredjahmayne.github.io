---
layout: post
title: Vehicle Dynamics & Performance Simulation
description: Deriving vehicle performance targets through tire data analysis, aerodynamic mapping, and engine simulation.
skills:
  - Tire Data Analysis (TTC)
  - Aerodynamic Target Setting
  - Engine Performance Modeling
  - MATLAB / Simulink
  - Data Visualization
main-image: /frictioneclipse.png
---

### Project Overview
My primary role as Vehicle Dynamics Lead was to transition the team from "rule of thumb" design to data-driven engineering. This involved creating a full vehicle performance model to set objective targets for the subsystem teams.

### 1. Tire Data Analysis & Handling Targets
I utilized raw data from the Formula SAE Tire Test Consortium (TTC) to characterize our tire performance. By fitting the data to curves, I calculated optimal targets for:
* **Slip Angle:** Identifying the peak lateral force to set steering geometry.
* **Understeer Gradient:** Modeled the vehicle's steady-state handling behavior to ensure neutral steer characteristics at the limit.

{% include image-gallery.html images="FY_v_SA.png, MZ_v_SA.png, ggdiagram.png, optimaltemp.png, understeergradient.png" height="300" %}

### 2. Aerodynamic Targets
I developed a sensitivity analysis to determine the point of diminishing returns for downforce vs. drag. These targets were passed to the Aero team to ensure the package was efficient for the specific average speeds of the FSAE competition.

{% include image-gallery.html images="aeroldratio.png, aerotargets.png" height="300" %}

### 3. Engine Performance & Gearing
To optimize straight-line acceleration, I modeled the engine's torque curve against various final drive ratios. This simulation allowed us to select a gearing ratio that maximized tractive effort in the endurance event's most common speed range.

{% include image-gallery.html images="engineT&PvRPM.png" height="300" %}

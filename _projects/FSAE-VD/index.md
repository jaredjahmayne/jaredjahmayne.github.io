---
layout: post
title: Vehicle Dynamics & Tire Modeling
description: Utilization of Tire Test Consortium (TTC) data to create predictive handling models, including understeer gradient and lateral load transfer distribution (LLTD).
skills:
  - MATLAB & Simulink
  - Tire Data Analysis (TTC)
  - Pacejka Magic Formula
  - Data Processing
  - Mathematical Modeling
main-image: /assets/vd-main-graph.png
---

### Project Overview
To validate the design decisions for the Titan XIX chassis, I developed a suite of MATLAB tools to analyze raw tire data from the Formula SAE Tire Test Consortium (TTC). The goal was to transition from "rule of thumb" design to data-driven vehicle dynamics.

### Tire Data Analysis
I wrote scripts to parse raw `.dat` files, filtering for specific camber angles and pressure ranges. By fitting this data to curves, I was able to determine:
* **Cornering Stiffness (C-alpha):** Calculating the initial slope of the force vs. slip curve to predict steering response.
* **Peak Grip:** Identifying the saturation point of the Hoosier tires to set maximum lateral G targets for the suspension team.

### Handling Predictions
Using these tire models, I calculated the theoretical **Understeer Gradient** for the vehicle. This allowed our team to:
1.  Tune the static weight distribution and aero center of pressure.
2.  Adjust roll stiffness distributions (sway bars) to shift the car towards neutral steer behavior at the limit.

### Gallery
{% include image-gallery.html images="vd-graph1.png, vd-graph2.png, vd-graph3.png" height="300" %}

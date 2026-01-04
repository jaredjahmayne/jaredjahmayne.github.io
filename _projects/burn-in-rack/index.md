---
layout: post
title: Amplifier Burn-In Process Implementation
description: Designed and built a mobile burn-in station to stress-test amplifiers, ensuring reliability and capturing early-life failures.
skills: 
  - Test Engineering
  - Fixture Design
  - Manufacturing Ops
  - Electrical Safety
  - Quality Assurance
main-image: /assets/images/fender-burn-in-rack-2.jpg
---

### Project Overview
During my internship at Fender, I was responsible for implementing a "burn-in" process for a specific line of amplifiers. The objective was to stress-test the units under load to trigger early component failures (infant mortality) before they reached final packaging, thereby reducing warranty claims.

### Design & Implementation
I designed and assembled a mobile rack system capable of testing multiple units simultaneously. Key engineering contributions included:

* **Load Simulation:** Integrated high-wattage wirewound resistors (dummy loads) to simulate speaker impedance. This allowed the amplifiers to be driven at working temperatures without generating excessive noise on the factory floor.
* **Custom Fixturing:** Designed and fabricated custom wooden base plates with specific geometry to securely hold the amplifier chassis. This prevented movement during transport and ensured consistent alignment with the test leads.
* **Electrical Integration:** Wired a centralized power distribution system to safely supply and monitor mains power for the units simultaneously.
* **Process Flow:** Built the system on a mobile wire-rack chassis, allowing the burn-in station to move seamlessly between the assembly line and the Quality Assurance (QA) station without unhooking the units.

### Results
* **Improved Quality Control:** The process successfully identified component defects (such as faulty tubes or capacitors) prior to shipment.
* **Efficiency:** Standardized the testing time and method, removing variability between different assembly technicians.

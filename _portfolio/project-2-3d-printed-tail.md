---
title: "3D Printed VTOL Drone"
excerpt: "Contributed to a rapid-prototyping project to build a low-cost, 15-lb VTOL drone. My role involved SolidWorks design for the tail, materials testing (PLA Aero, PETG), and 3D printing of structural components.<br/><img src='/images/3d_print_aircraft.png'>"
collection: portfolio
---

### Project Overview
This project's goal was to design and build a field-ready, fixed-wing VTOL drone using rapid prototyping and US-sourced components. The primary objective was to produce an inexpensive, modular airframe capable of carrying a 1.5-pound payload with a 60-minute flight endurance.

### My Role & Contributions
My responsibilities focused on the airframe design, material selection, and fabrication:

* **CAD Modeling:** I designed the modular, inverted V-tail assembly in SolidWorks to be lightweight and 3D-printable.
* **Prototyping & Fabrication:** I operated a Bambu Carbon X-1 printer to fabricate the wing and tail sections.
* **Materials Research:** I tested and validated properties of PLA Aero and Carbon-Infused PETG, analyzing their trade-offs between strength, weight, and printability. We ultimately selected the Carbon-Infused PETG for its superior stiffness, despite it being a difficult filament to print.

![3D Printed Inverted V-Tail](/images/3d_print_tail.png){:loading="lazy"}

### Key Objectives & Constraints
The airframe was designed to meet the following requirements:
* 15-pound gross takeoff weight (GTOW)
* 1.5-pound payload capability (to carry an AgEagle Altum-PT sensor)
* 60-minute target flight time
* 15-25 m/s cruise speed
* Standard avionics (Orange Cube, radios, etc.)
* Modular design for field packability, assembly, and repair
* US-sourced components for inexpensive manufacturing

### Technical Design
* **Wing & Tail:** 3D printed modular sections (Carbon Infused PETG) covered with an Oratex skin.
* **Fuselage:** 3D printed modular structure with a removable skin for avionics access.

![SolidWorks VTOL Assembly](/images/VTOL_Solidworks.png){:loading="lazy"}

### Outcomes & Lessons Learned
The project successfully produced a modular, low-cost airframe that met the payload, avionics, and manufacturing requirements. The 60-minute flight time proved challenging, and the design process revealed several key lessons:

* **Structural Considerations:** The initial wing design required more reinforcement to handle torsional forces at the center, highlighting the structural demands of a high-aspect-ratio wing.
* **Component Placement:** The pusher motor's placement had a major impact on the center of gravity (CG), requiring careful balancing with battery placement.
* **Material Selection:** While strong, Carbon-Infused PETG proved challenging for printing long, thin structures like wing spars, requiring specialized printer settings and support strategies.

### Recommended Future Work
* **Wing Strengthening:** Integrate a larger, more robust spar or implement a composite skin to better manage torsional forces.
* **CG Balancing:** Move the pusher motor forward in the design to improve CG balance.
* **Spar Sizing:** Enlarge the spar used for the VTOL motor mounts to increase rigidity and reduce vibration.

![Assembled 3D Printed VTOL Drone](/images/3d_print_aircraft.png){:loading="lazy"}
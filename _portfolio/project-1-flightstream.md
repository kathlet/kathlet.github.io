---
title: "FlightStream: F-16 Aerodynamic Modeling"
excerpt: "Surface-panel aerodynamic model and derivative extraction for an F-16 baseline using FlightStream<br/><img src='/images/flightstream.png'>"
collection: portfolio
---

### Project Overview
This project focused on using FlightStream to build a high-fidelity, surface-panel aerodynamic model of a scaled F-16.

### Objectives
The primary goal was to compute a complete set of static and dynamic aerodynamic derivatives. This involved CAD preparation, meshing, running parameter sweeps, extracting coefficients, and validating the results against published NASA and MachUp datasets.

![FlightStream Surface Components with Deflected Horizontal Stabilizers](/images/flightstream_surface.png){:loading="lazy"}

### My Role & Contributions
* Imported and prepared SolidWorks CAD geometry for panel discretization.
* Generated a surface panel mesh tuned for FlightStream by component.
* Defined flight control surfaces (flaperons, stabilators) and parametrized deflection cases.
* Executed systematic parameter sweeps to produce datasets for static and "dynamic derivative estimation.
* Calculated aerodynamic coefficients and derivatives by post-processing case outputs.
* Automated post-processing with Python scripts to extract coefficients and produce summary plots and tables.

![FlightStream Example Mesh for the Horizontal Stabilizers](/images/flightstream_mesh.png){:loading="lazy"}

### Outcomes & Results
* Produced a complete set of static and dynamic derivatives for the baseline configuration.
* Initial results showed good correlation with NASA and MachUp reference data, validating the modeling approach and setup.
* Generated reproducible scripts and documentation to re-run sweeps and regenerate results.

![FlightStream Pressure Plot](/images/flightstream.png){:loading="lazy"}

### Tools & Technologies
* **FlightStream** (including scripting and sweep automation)
* **SolidWorks** (CAD prep)
* **Python** (post-processing, plotting)
* **Git** (version control)



---
title: "FlightStream: F-16 Aerodynamic Modeling"
excerpt: "Surface-panel aerodynamic model and derivative extraction for an F-16 baseline using FlightStream<br/><img src='/images/flightstream.png'>"
collection: portfolio
---

Overview
======
I used FlightStream to build a surface-panel aerodynamic model of a scaled F-16 and to compute static and dynamic aerodynamic derivatives. The project included CAD preparation, meshing, running parameter sweeps, extracting coefficients, and validating results against published datasets (NASA, MachUp).

![FlightStream Surface Components](/images/flightstream_surface.png){:loading="lazy"}
![FlightStream Mesh](/images/flightstream_mesh.png){:loading="lazy"}
![FlightStream Pressure Plot](/images/flightstream.png){:loading="lazy"}

Key responsibilities
======
- Imported and prepared SolidWorks CAD geometry for panel discretization.
- Generated surface panel mesh tuned for FlightStream (resolution and smoothing choices documented in notes).
- Defined flight control surfaces (flaperons, stabilators) and parametrized deflection cases.
- Executed systematic parameter sweeps to produce datasets for static and dynamic derivative estimation.
- Calculated aerodynamic coefficients and derivatives by post-processing case outputs.
- Automated post-processing with Python scripts to extract coefficients and produce summary plots and tables.

Results
======
- Produced a complete set of static and dynamic derivatives for the baseline configuration.
- Initial results showed good correlation with NASA and MachUp reference data, validating the modeling approach and setup.
- Generated reproducible scripts and documentation to re-run sweeps and regenerate results.

Tools & technologies
======
- FlightStream (scripting and sweep automation)
- SolidWorks (CAD prep)
- Python (post-processing, plotting)
- Git (version control)



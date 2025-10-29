---
title: "Aerodynamic Solvers: 2D Panel Method & Lifting-Line Methods"
excerpt: "Developed and implemented two computational aerodynamics solvers: a 2D potential flow panel method for airfoil analysis and a lifting-line theory model for finite wings. These tools analyze aerodynamic coefficients, pressure distributions, and spanwise lift distributions.<br/><img src='/images/potential_flow_airfoil.png'>"
collection: portfolio
---

Project Overview
-----

This project showcases the development of two foundational aerodynamics solvers in Python, built from fundamental principles. The first is a 2D potential flow solver (a panel method) used to analyze airfoil sections. The second is a 3D lifting-line theory (LLT) solver for finite wings.

Together, these tools demonstrate a comprehensive approach to modeling and predicting aerodynamic performance, from 2D pressure distributions and lift curves to 3D spanwise lift distributions and wing performance.

2D Airfoil Panel Method
-----

The first part of this project involved creating a 2D panel method solver. The objective was to create a robust tool capable of modeling inviscid, incompressible flow over arbitrary 2D airfoils to predict their aerodynamic properties.

![Potential Flow Over a Cylindar](/images/potential_flow_cylinder.png){:loading="lazy"}

This solver's capabilities are demonstrated in the included PDF report, which covers a variety of examples showcasing the functionality of the solver.

![Potential Flow Over an Airfoil](/images/potential_flow_airfoil.png){:loading="lazy"}

### Functionality
* ***Streamline Visualization:*** Plots potential flow streamlines around various airfoil geometries (like the NACA 2412, 2421, and 0015) at different angles of attack to visualize flow behavior.
* ***Lift Curve Validation:*** Generates lift-curve slopes ($C_L$ vs. $\alpha$) and validates them against experimental data, thin airfoil theory, and other established solvers like XFOIL.
* ***Pressure Distribution:*** Calculates and plots the pressure coefficient ($C_p$) distribution over an airfoil's surface. This is essential for identifying regions of high and low pressure and for calculating the overall lift.

![Pressure Plot Over an Airfoil](/images/pressure_plot.png){:loading="lazy"}

Lifting-Line Theory
-----

The second part of this project, expands the 2D analysis to a 3D finite wing using Prandtl's Lifting-Line Theory (LLT). This model is crucial for understanding the effects of finite span, including induced drag and spanwise lift distribution.

![Example Output from the Lifting-Line Code](/images/wing_project.png){:loading="lazy"}

### Key Functionality:

* ***Fourier Series Solution:*** Solves for the wing's circulation distribution by representing it as a Fourier series. This allows for the calculation of aerodynamic coefficients from a set of Fourier coefficients ($a, b, c, d$).
* ***Spanwise Lift Distribution:*** Plots the distribution of lift across the wingspan ($z/b$) and, most importantly, decomposes the total lift into its fundamental components.
* ***Component Analysis:*** The solver isolates the aerodynamic contributions from:
    * ***Symmetric Loading:*** Wing planform geometry (angle of attack) and wing twist (washout).
    * ***Asymmetric Loading:*** Control surface deflection (ailerons) and vehicle motion (roll rate).
* ***Aerodynamic Coefficients:*** Integrates the spanwise distributions to find the total wing's aerodynamic coefficients, including the lift coefficient ($C_L$), induced drag coefficient ($C_{Di}$), rolling moment coefficient ($C_l$), and yawing moment coefficient ($C_n$).
* ***Planform Visualization:*** Includes a plotting function to visualize the wing's planform geometry, taper, and aileron locations.


Full 2D Solver Report
-----

<div style="position:relative;padding-bottom:140%;height:0;overflow:hidden;"> <iframe src="{{ '/files/A11_A26.pdf' | relative_url }}" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0"></iframe> </div> <p><a href="{{ '/files/A11_A26.pdf' | relative_url }}">Download the PDF (A11–A26)</a></p>





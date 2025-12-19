---
layout: project
title: Wind Turbine Blade Design
description: Wind Turbine Blade Design
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/bladecoverphoto.png
---

For my fluids and heat transfer laboratory class, we were tasked with designing a small-scale horiztonal-axis wind turbine blade designed to maximize extracted power while operating across a range of wind speeds at a given RPM. The wind turbine is optimized for use in an oncoming wind velocity of 4.8 m/s, the average velocity that would extract max power under its experienced Weibull distribution of velocities. To design the blade, a MATLAB model was developed to optimize the design. This included selecting an airfoil designation of NACA 4412, determining chord length and pitch as a function of radius, solving for the forces and stresses experienced by the blade, predicting output power curves, and iterating to determine the design angular velocity. The chosen design predicted a design RPM of 1050 that would extract 3.61 W at an oncoming wind speed of 4.82 m/s. The designed wind turbine was then tested at five different oncoming wind speeds, and experimental power graphs were recorded for each. Comparing the model predicted behavior with the experimental behavior, the actual wind turbine produced less power but spun faster, likely a result of the model’s assumptions and simplifications, such as not taking into account tip effects. The maximum power extracted observed was 1.8 W at an oncoming wind speed of 5.8 m/s. Ultimately, while the wind turbine underperformed relative to what the model predicted, the performance demonstrates how optimizing the taper, twist, and CL/CD can result in a blade that maximizes power output under a given Weibull distribution.


<center>
<img src="/fa25-portfolio-ellayellin/assets/images/bladerender.png" alt="bladeCad" width="500"/>
<br>
<strong>Figure 1:</strong> CAD render of final blade design.
</center>
<br>
<center>
<img src="/fa25-portfolio-ellayellin/assets/images/powercurves.png" alt="powerCurves" width="500"/>
<br>
<strong>Figure 2:</strong> Experimentally collected power curves showing a maximum extracted power of 1.8 W.
</center>
<br>
---
layout: project
title: MAE 3270 Torque Wrench FEM
description: FEM of a Torque Wrench w/ Applied Loading 
technologies: [Fusion 360, ANSYS Mechanical]
image: /assets/images/torquewrench.jpg
---
[Download my analysis]({{ "/assets/3270.pdf" | relative_url }})

This project involves the complete design and analysis of an instrumented torque wrench rated for 600 in-lbf, integrating multiple mechanical engineering discipçlines including materials selection, stress analysis, fracture mechanics, fatigue design, CAD modeling, and finite element analysis. The torque wrench uses strain gauge technology to transduce applied torque into an electrical signal, with a design goal of maximizing sensitivity (mV/V output) while ensuring structural integrity under cyclic loading.

The design process began with analytical hand calculations using beam theory to establish baseline dimensions and material properties, followed by iteration to optimize the design against multiple competing constraints: achieving minimum 1.0 mV/V strain gauge sensitivity, maintaining a safety factor of 4 for yield failure, a safety factor of 2 against fracture from an initial crack, and a fatigue safety factor of 1.5 for 10⁶ fully-reversed load cycles. AerMet 100 steel was selected for its exceptional combination of strength (310 ksi), fracture toughness (137 ksi√in), and fatigue resistance (131 ksi at 10⁶ cycles).

The final design was created in Autodesk Fusion 360 and imported into ANSYS Mechanical for finite element validation. FEM results confirmed a maximum stress of 52.1 ksi, load point deflection of 0.698 inches, and strain of 1869 microstrain at the gauge location, yielding a sensitivity of 1.86 mV/V using a half-bridge Wheatstone configuration with CEA-06-125UNA-350 strain gauges. This project demonstrates the complete engineering design cycle from analytical calculations through computational validation, showcasing proficiency in modern CAD/FEM tools and fundamental mechanical design principles.



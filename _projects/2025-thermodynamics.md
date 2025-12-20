---
layout: project
title: Thermodynamic System Analysis
description: Applying Thermodynamic Concepts to Niagara Falls
technologies: [Thermodynamics]
image: /assets/images/thermo/thermo-7.png
---


# Niagara Fals - The Rankine Generation Station

**Isaac Kahn, Bridget McAvoy, Deepti Kousik**  
**ENGRD 2210** 

---

## Chosen Device or System:
**Niagara Falls Turbines**

---

<div class="image-grid">
  <img src="/assets/images/thermo/thermo-1.png" alt="Niagara Falls Power Station Overview">
  <img src="/assets/images/thermo/thermo-2.png" alt="Niagara Falls Turbine Diagram">
  <img src="/assets/images/thermo/thermo-3.png" alt="Interior of Power Station">
  <img src="/assets/images/thermo/thermo-4.png" alt="Historical Power Station View">
</div>

## Qualitative Description

The Rankine Generating Station was built between 1901 and 1905 by the Canadian Niagara Power Company on the Canada side of Niagara Falls. It was named after its founder, William Birch Rankine and did not employ a Rankine Cycle. Instead, it generated hydroelectric power from the gravitational potential energy of the Niagara River before the falls. For 100 years it provided power to the surrounding area before closing in 2005. The closing was due to the generators outputting 25Hz AC current (as opposed to the modern American standard of 60Hz), and the turbine shafts slipping out of alignment. 

First, the river was diverted into a forebay. Then, it flowed through penstocks (a pipe) into the eleven turbines that made up this generating station. These Francis turbines converted this energy into work. Francis Turbines are radial flow and are optimized for high pressure, low flow rate applications. For our analysis, we assume changes in kinetic energy and enthalpy of the water from the top of the penstock to the outlet of the turbine are negligible. We sourced values from various websites for mass flow rate, change in height, and output power to calculate the efficiency of the Rankine generating station. These turbines had a cumulative power output of 76.4MW, although this dwindled before the station’s closing in 2005. 


---

## System Diagrams

<img src="/assets/images/thermo/thermo-5.png" alt="System Diagram of Niagara Falls Turbines" class="center-image">

<div class="image-grid">
  <img src="/assets/images/thermo/thermo-6.png" alt="Turbine">
  <img src="/assets/images/thermo/thermo-7.png" alt="Flow Path Visualization">
</div>


---

**Mass Balance**


$$
\dot{m}_{in} = \dot{m}_{out}
$$

**Energy Balance**

$$
\dot{E}_{CV} = 0
= -\dot{W}_{shaft}
+ \dot{m}
\left(
\frac{v_{in}^2 - v_{out}^2}{2}
+ h_{in} - h_{out}
+ g (z_{in} - z_{out})
\right)
$$


$$
\dot{W}_{shaft}
= \dot{m} g (z_{in} - z_{out})
$$


$$
\dot{W}_{shaft}
= (0.1 \times 1600 \, \text{m}^3/\text{s} \times 1000 \, \text{kg}/\text{m}^3)
(9.81 \, \text{m}/\text{s}^2)
(54.9 \, \text{m})
= 86.2 \, \text{MW}
$$

$$
\eta
= \frac{W_{act}}{W_{shaft}}
= \frac{76.4}{86.2}
= 88.7\%
$$


---

## Changes to Operating Conditions

There are several changes that could be made to the operation of the turbine. Increasing the water level of the river/reservoir (the forebay), optimizing the intake gates (the penstock), or lowering the level of the turbine pit would all increase the height of the fall that the working fluid experiences. This can result in a higher flow rate through the turbines, which will result in a greater power output. More energy is also extracted per unit of water, likewise increasing the output power, but these changes can have detrimental effects. This could increase the stress on elements of the turbines, reduce operational lifetime, cause cavitation, and increase risk of system failure

Turbines also have optimal flow ranges where efficiency is highest. Increasing flow beyond this point can result in turbulence and hydraulic losses, while operating below this point will similarly be inefficient. Thus, extracting maximum energy must be balanced with the system conditions. Refurbishing the turbine blades to reduce turbulence will improve the turbine efficiency and minimize hydraulic losses, changing the power output without having to change the overall height of the fall. Reducing turbulence in other parts of the system - namely, the penstocks and the forebay - will help ensure the fluid reaches the turbines without significant energy losses due to friction and will help maximize overall efficiency. 	


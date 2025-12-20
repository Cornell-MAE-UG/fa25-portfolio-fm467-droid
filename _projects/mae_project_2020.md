---
layout: project
title: Heat Exchanger Final
description: Experimenting with a Parallel vs Counter-flow Heat Exchanger
image: /assets/images/HeatEchange.png
---


Amina Lesbekova al2588
Fatima Moizuddin fm467


In this lab we analyzed a real water-to-water heat exchanger and compared its performance in parallel flow and counterflow configurations. Our goals were to (1) describe how the exchanger works physically, (2) apply mass, energy, and entropy balances to a real system, and (3) determine how changing an operating/design condition changes performance. Heat exchangers like this are central to many engineering systems, including car radiators, HVAC units, power-plant condensers and feedwater heaters, chemical reactors with cooling jackets, and refrigeration systems. Therefore, this lab provided us with a realistic thermodynamics outcome to share with employers.

A heat exchanger is a device that transfers heat from a hot fluid to a cold fluid without allowing the two fluids to mix. The fluids flow through separate channels, and heat moves through the wall from the hotter side to the colder side. As the hot fluid releases heat and cools down, the cold fluid absorbs that heat and warms up. They can be arranged in both parallel flow where both fluids move in the same direction, or counterflow where they move in opposite directions.
In a heat exchanger, parallel flow means both fluids move in the same direction, so the temperature difference is largest only at the inlet and quickly decreases. This leads to lower heat transfer. Counterflow places the fluids in opposite directions, keeping a larger temperature difference throughout the exchanger, which increases heat transfer and gives better heating of the cold fluid. Starting the hot fluid at a higher temperature also increases the temperature difference, allowing more heat to transfer in both flow arrangements, with counterflow benefiting the most.

We tested two configurations:
Parallel flow: hot and cold streams flow in the same direction. The temperature difference is largest at the inlet and decreases quickly along the exchanger length.
Counterflow: hot and cold streams flow in opposite directions. This maintains a larger temperature difference over a greater portion of the exchanger, allowing counterflow to transfer more heat for the same inlet conditions. Based on this stiffness requirement, a mass-efficient hollow rectangular aluminum (6061-T6) cross-section was selected. This section satisfied the minimum second moment of area while minimizing structural mass and keeping deflection within acceptable limits. Throughout the design process, actuator force limits, geometric constraints, and material efficiency were used as the primary criteria for all engineering decisions, ensuring that the final design achieved the highest possible mechanical performance within the stated constraints.

![Alt text]({{ "/assets/images/chematic.png" | relative_url }}){: .inline-image-r style="width: 200px"}

![Alt text]({{ "/assets/images/CV.png" | relative_url }}){: .inline-image-r style="width: 200px"}

![Alt text]({{ "/assets/images/TABLE.png" | relative_url }}){: .inline-image-r style="width: 200px"}

![Alt text]({{ "/assets/images/Calculation.png" | relative_url }}){: .inline-image-r style="width: 200px"}

![Alt text]({{ "/assets/images/DATA.png" | relative_url }}){: .inline-image-r style="width: 200px"}


Observation: Based on the cold-side measurements, the exchanger transferred roughly 8–13 kW across our runs.
We expect some mismatch in Qc and Qh because of real-system effects, heat loss from tubing/exchanger to the room, unequal pump flow rates, imperfect reservoir mixing, and thermometer lag/placement. This is typical outside ideal textbook conditions.

![Alt text]({{ "/assets/images/EFFECTIVE_NE.png" | relative_url }}){: .inline-image-r style="width: 200px"}


For the most fair comparison between flow arrangements, we looked at our second parallel-flow run and our first counterflow run because they began with nearly the same hot-side starting temperature, around 35 degrees Celsius, and very similar cold-side starting temperatures. Under these matched conditions, the counterflow setup performed a little better: it achieved a slightly higher effectiveness and transferred heat to the cold stream at a slightly greater rate than the parallel-flow setup. 

Conclusions: From this lab we demonstrated real thermodynamic analysis of a working heat exchanger: We measured cold-side heat transfer rates of roughly 8–13 kW. Under similar inlet conditions, counterflow produced higher effectiveness (0.50) than parallel flow (0.47). Increasing hot-reservoir inlet temperature in counterflow increased heat transfer by about 8% Energy-rate mismatches between sides were expected due to real losses and uneven flow.

Overall, this experiment gave us a concrete example of applying mass, energy, and entropy balances to a real device, and it showed how both a design change (flow arrangement) and an operating change (hot inlet temperature) directly affect heat-exchanger performance.



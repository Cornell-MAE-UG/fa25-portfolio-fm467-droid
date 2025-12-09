---
layout: project
title: Design of an Actuator 
description: Just an Actunator that I designed
image: /assets/images/IMG_3065.jpg
---


For this project, I designed a planar lifting mechanism operating inside a two-dimensional workspace of 150 cm in length and 50 cm in height. The mechanism consists of a rigid bar of fixed length (1.45 m) supported by three pin joints, with two pins rigidly mounted to the ground to satisfy the required boundary conditions. A linear actuator was selected from an online catalog based on its maximum rated force capacity (50 kN), and it was modeled as an ideal two-force member capable of applying pure axial tension and compression.

During the initial design stage, all components—including the bar, pin supports, and actuator-were assumed to be perfectly rigid in order to simplify the static equilibrium analysis. The primary design objective was to maximize both the lifting height and the maximum liftable load within the restricted design envelope. To achieve this, the actuator attachment point was placed 0.35 m from the main ground pin in order to maximize the effective moment arm while maintaining feasible geometry throughout the range of motion.

Using static equilibrium, I performed a moment balance about the primary ground pin to relate the actuator force capacity to the maximum allowable lifted load. This analysis showed that the mechanism could theoretically lift approximately 12.07 kN under ideal geometric conditions. After establishing the load capacity using rigid-body statics, I extended the design to include beam bending effects by modeling the bar as a cantilever beam. A serviceability limit of 2% of the bar length was enforced, allowing the required second moment of area to be calculated.

Based on this stiffness requirement, a mass-efficient hollow rectangular aluminum (6061-T6) cross-section was selected. This section satisfied the minimum second moment of area while minimizing structural mass and keeping deflection within acceptable limits. Throughout the design process, actuator force limits, geometric constraints, and material efficiency were used as the primary criteria for all engineering decisions, ensuring that the final design achieved the highest possible mechanical performance within the stated constraints.

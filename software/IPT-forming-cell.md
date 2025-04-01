---
permalink: /IPT-forming-cell/
---

# Forming Cell In-Plane Tensioning (IPT) modules

This subroutine (VDISP) for the Finite Element package Abaqus/Explicit allows to apply on the models, the same boundary conditions as that applied by the in-plane tensioning (IPT) modules in the forming cell used in Chen et al. [1]. Adequate prescription of the displacement, velocity and acceleration at different stages, allow to effectively simulate the tension applied by the gripper to the fabric. In the initial state of forming, i.e. when the sum of all internal forces acting on the force applied node is less than the weight magnitude, displacement of this node is set to zero; once the internal forces exceeded the weight, acceleration is set to the difference between the two forces divided by the node’s equivalent mass and is updated in each iteration. Additionally, friction between the gripper and the tool is included (coefficient = 1.05, both surfaces are aluminium) and is represented as an acceleration term in the opposite direction to the previous velocity increment.

## Access

To receive access to the code, please send a short email to bci-github@bristol.ac.uk to let us know your interest.

You can click [here](mailto:bci-github@bristol.ac.uk?subject=Access%20to%20IPT-forming-cell%20repository&body=Dear%20BCI%2C%20%0D%0A%0D%0AI%20would%20like%20to%20request%20access%20to%20your%20GitHub%20repository%20for%20IPT-forming-cell.%20%0D%0A%0D%0ABest%20wishes%2C%20%0D%0A%3Cname%3E%0D%0A%3Coptional%20affiliation%3E) for a template.

## Additional details

A full technical description of the model coded in the UMAT is provided in:

1. Siyuan Chen, Adam Thompson, Tim Dodwell, Stephen Hallett, and Jonathan Belnoue, *A comparison between robust design and digital twin approaches for Non-Crimp fabric (NCF) forming*, Composites Part A: Applied Science and Manufacturing, **193**, 108864 (2025). [https://doi.org/10.1016/j.compositesa.2025.108864](https://doi.org/10.1016/j.compositesa.2025.108864)

For more information please contact: Bristol Composites Institute (University of Bristol) [bci-github@bristol.ac.uk](bci-github@bristol.ac.uk).


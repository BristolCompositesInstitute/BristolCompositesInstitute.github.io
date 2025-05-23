---
layout: default
---

# Bristol Composites Institute

The [Bristol Composites Institute (ACCIS)](http://www.bris.ac.uk/composites),
based at the University of Bristol, UK, brings together composites activities
across the University. It combines cutting-edge fundamental science with strong
industrial links for exploitation and technology transfer, and acts as focus
for collaboration, both nationally and internationally.

This page collects the various research codes that the BCI has made
available to the academic community. The codes are hosted on GitHub via
the [BCI organisation page](https://github.com/BristolCompositesInstitute). 
Please contact <bci-github@bristol.ac.uk> for access.

# NOTICE 
You are currently viewing the _new_ Bristol Composites Institute Github Page.
If you have been redirected here from the old ACCIS Github Page, and would like
to view the old organisation instead, please click 
[here](https://accis.github.io/archive)

# Software

| Project | Description |
| --------- | ------------- |
| [DefGen (umat)]({% link software/DefGen.md %}) | This repository encloses a UMAT subroutine for the Finite Element software Abaqus. Given a determined cycle of pressure and temperature, the subroutine allows to make predictions for the the final thickness, fibre volume fraction and defects formed during the processing of composte parts manufactured through the prepreg technology. The code is at the basis of the recent work on defect formation performed at the university of Bristol (references included). |
| [HypoDrape]({% link software/HypoDrape.md %}) |Hypodrape is a usermaterial subroutine (VUMAT) for Abaqus/Explicit used to define the mechanical constitutive behaviour of biaxial textile materials for simulating fabric drape and forming.|
| [DefGen (python)]({% link software/DefGen_1D.md %}) | This directory contains all the files of the DefGen ProToCoL material model (Python implementation) for the modelling of the toughened prepregs’ compaction response under processing conditions. |
| [DefGen Parameter extraction]({% link software/DefGenParFit.md %}) | This directory contains the implementation of the parameter extraction framework used for the analysis of the compaction data within the DefGen ProToCoL material model. |
| [SimpleCure]({% link software/simplecure.md %}) | This project was developed to increase awareness of how thermal management modelling can be used to help guide design and production of composite structures in industry. The tools predict the 1D heat transfer in composites manufacturing processes with varying processing conditions, material properties, and geometries. User guide and tutorial are included. |
| [PlyExtraction]({% link software/PlyExtraction.md %}) | This software tool can process laminate sample images and construct detailed geometric finite element models in a fast and automated manner with minimal user interaction. The finite element models can be used directly for structural and strength simulations to analyse the effect of ply waviness defects. |
| [Thick-Adhesive-Joints-Failure]({% link software/Thick-adhesive-joints-failure.md %}) | This directory contains all the files necessary to run the LS-Dyna UMAT developed at the University of Bristol for the simulation of thick adhesive joints failure. |
| [MultiScale 2D woven]({% link software/Multi-scale-2D-woven.md %}) | This two-module Python package allows users to create pre-sheared 2D woven RVEs, homogenise their material properties, and apply them in component-scale shell models. |
| [Forming Cell In-Plane Tensioning (IPT) modules]({% link software/IPT-forming-cell.md %}) | This vdisp subroutine applies the boundary conditions in the in-plane tensioning (IPT) modules in the forming cell. |
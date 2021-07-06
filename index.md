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
| [Unity Drape Simulator](https://shashitha-kularatna.itch.io/unity-drape-simulator) | Unity Drape Simulator (UDS) is software that simulates the hand layup process of woven prepreg/dry reinforcement. UDS is a Kinematic drape simulator, which models woven reinforcement using a pin-jointed net. In this trial version, 5 different mold geometries are made available to the user to understand the working mechanics of UDS. A link to a demo video is also embedded within the software for new users. |

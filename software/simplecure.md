---
permalink: /simplecure/
---

# Introduction

**SimpleCure** was developed between the National Composites Centre and the University of Bristol using High-Value Manufacturing Catapult funds with the aim of demonstrating the power of thermal modelling to the UK composites industry. A series of four Microsoft Excel spreadsheets were created having different boundary conditions that are commonly found in composites manufacture. Thermal material models are implemented in 1D so the user can identify time to cure and maximum overshoot for a given processing cycle. While there are a variety of ways to simulate the heat transfer in composites manufacture, the main aim here is awareness of the possibilities.

# Access
To receive access to the SimpleCure repository, please send a short email to bci-github@bristol.ac.uk to let us know your interest.   

Access is granted on the condition that you agree for us to contact you about your use of the software.

You can click [here](mailto:bci-github@bristol.ac.uk?subject=Access%20to%20SimpleCure%20repository&body=Dear%20BCI%2C%20%0D%0A%0D%0AI%20would%20like%20to%20request%20access%20to%20your%20GitHub%20repository%20for%20SimpleCure.%20%0D%0A%0D%0ABest%20wishes%2C%20%0D%0A%3Cname%3E%0D%0A%3Coptional%20affiliation%3E) for a template.


# Contents

## Tools

| Title                       | Description                                                   |
| --------------------------- | ------------------------------------------------------------- |
| `SimpleCure_Autoclave.xlsm` | Autoclave curing processes having convective heat transfer on both sides of the part/tool |                     |
| `SimpleCure_Infusion.xlsm`  | Curing after resin infusion processes having natural convection on one side and a prescribed temperature on one side of the part |                |
| `SimpleCure_Oven.xlsm`      | Oven curing processes with convective heat transfer on one side and a prescribed temperature on one side of the part |
| `SimpleCure_RTM.xlsm`       | Curing after resin transfer moulding processes (RTM) with prescribed temperature on both sides of the part |

## Documentation

| Title           | Description           |
| --------------- | --------------------- |
| `UserGuide.pdf` | SimpleCure User Guide |
| `Tutorial.pdf`  | SimpleCure Tutorial   |

## License

| Title     | Description |
| --------- | ----------- |
| `LICENSE` | SimpleCure is distributed under the [MIT license](https://choosealicense.com/licenses/mit/) |

# References
 
All material models in the case study presented in SimpleCure\_Autoclave can be found in:

 * Mesogitis T, Kratz J, Skordos AA. *Heat transfer simulation of the cure of thermoplastic particle interleaf carbon fibre epoxy prepregs.* Journal of Composite Materials. 2019. 53(15), 2053–2064. https://doi.org/10.1177/0021998318818245

The underpinning data for the models in the above paper can be found in the [University of Bristol data repository](https://data.bris.ac.uk/data/dataset/3utcijc5qldfl2j70blaey80vo)

All material models in the case study presented in SimpleCure\_RTM and SimpleCure\_Infusion can be found in:

 * Mesogitis T, Skordos AA, Long AC. *Stochastic simulation of the influence of cure kinetics uncertainty on composites cure. Composites Science and Technology.* 2015 Apr 6;110:145-51.

All material models in the case study (MTM45-1) presented in SimpleCure\_Oven can be found in:

 * Kratz J, Hsiao K, Fernlund G, Hubert P. *Thermal models for MTM45-1 and Cycom 5320 out-of-autoclave prepreg resins.* Journal of Composite Materials. 2013 Feb;47(3):341-52.


---
layout: page
title: Projects
permalink: /projects
---

## Reasearch projects

### 1. Modelling of solidification cracking in laser based additive manufacturing
Additive manufacturing provides the means by which complicated shapes, which can not be manufactured elegantly with conventional methods, can be fabricated. The mechanics of heat transfer that occur during this process is very different from the conventional methods like casting as the  molten region is very small and the cooling rates achieved are much higher. Though such high cooling rates are essential they tend to increase the cracking susceptibility of the material. The weld pool characteristics play an important role in the cracking susceptibility of the alloy. Hence effort was undertaken to model the 3D heat transfer during the additive manufacturing process to accurately predict the weld pool morphology. The modelling was done using [OpenFOAM](https://openfoam.org) , an open-sourced  software for CFD. This can be then used to calculate the residual stress in the domain which can then provide a measure of cracking susceptibility of the system. 


### 2. Internship at [John Deere](https://www.deere.co.in/en/john-deere-technology-center/john-deere-asia-technology)
I modellied the microstructural evolution of steels using phase field techniques. The codes were developed in Fortran the pahse field equations and integrated with an Finite-Element code to solve for the elastic stress and strains. The microstructural evolutions during austenite-ferrite and eutectic transformations were modelled and compared with experimental observations. 

### 3. Simulation of deep penetration welding using OpenCL on GPU
Evaporation and enhanced absorption of heat are involved in achieving deep penetration during welding. Such a mode is referred to as keyhole mode in electron beam welding. Thermal characteristics during keyhole mode welding play a significant role in the microstructure evolution of the weld. Understanding the evolution of the keyhole will also enable prediction of porosity and crack  susceptibility during welding. Simulation of the keyhole requires modelling of heat transfer in three dimensions while simultaneously taking into account the solid-liquid and liquid-vapour interactions. This complex phenomenon, when coupled with the small grid size and time steps required, increases the computation cost significantly. Graphical Processing Units (GPU) can significantly reduce the simulation time. [OpenCL](https://www.khronos.org/opencl/) is open source and also has cross-platform compatibility which makes the code portable. In this work, an attempt was made to model the characteristics of the keyhole during electron beam welding of beta Ti alloy using GPUs. The simulation was benchmarked with experimental studies and the difference in simulation times between CPU and GPU implementation was also quantified to understand the effect of GPU on the runtime. The effect of the electron beam radius on the keyhole was parameterised to determine the optimal processing condition.


### 4. Hot cracking susceptibility of Ni-based superalloys during laser based additive manufacturing

I used in-house codes to model the heat transfer during Additive manufacturing process. 
This was then used as an input to the phase field codes to predict the morphology of the system.  



### 5. Study of grain growth characteristics in spark plama sintered MgO

The goal was to model the growth charecteristics of MgO as a function of the processing parameters. Through this we were able to deduce the effect of electric current, pressure, temperature on the growth of nano MgO powders. I performed ball milling to achieve nano powders for used XRD,  optical and scanning electron microscopy to charecterise the samples before and after sintering.  


## Course projects


### 1. Flow in a channel with an obstacle

### 2. Calculation of Interfacial energies for $\theta'$ precipitates in Al-Cu matrix

### 3. Effect of an inhomogenity on a dislocation 


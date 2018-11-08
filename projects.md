---
layout: page
title: Projects
permalink: /projects
---

## Reasearch projects

### 1. Modelling of solidification cracking in laser based additive manufacturing
Additive manufacturing provides the means by which complicated shapes, which can not be manufactured elegantly with conventional methods, can be fabricated. The mechanics of heat transfer that occur during this process is very different from the conventional methods like casting as the  molten region is very small and the cooling rates achieved are much higher. Though such high cooling rates are essential they tend to increase the cracking susceptibility of the material. The weld pool characteristics play an important role in the cracking susceptibility of the alloy. Hence effort was undertaken to model the 3D heat transfer during the additive manufacturing process to accurately predict the weld pool morphology. The modelling was done using [OpenFOAM](https://openfoam.org) , an open-sourced  software for CFD. This can be then used to calculate the residual stress in the domain which can then provide a measure of cracking susceptibility of the system. 


### 2. Internship at [John Deere](https://www.deere.co.in/en/john-deere-technology-center/john-deere-asia-technology)
Microstructure of an alloy determines its mechanical properties to a great extent. The effect of microstructure and its effect on the mechanical behaviour is widely documented. The effect of processing conditions on the microstructure is of active inteest and understanding this relation can help us in optimising the processing conditions to obtain superior properties. Phase field modelling has been successful in modelling evolution of microstructure. In this project codes were developed in FORTRAN to solve the Multi Phase Field equations which was coupled with Abaqus to solve the elasticity equations. Diffusion equation was also incorporated to model the compostion evolution. The Austenite to Ferrite transformation and the Eutectic transformations were modelled and the microstructures obtained were compared with experimental micrographs. 

### 3. Simulation of deep penetration welding using OpenCL on GPU
Evaporation and enhanced absorption of heat are involved in achieving deep penetration during welding. Such a mode is referred to as keyhole mode in electron beam welding. Thermal characteristics during keyhole mode welding play a significant role in the microstructure evolution of the weld. Understanding the evolution of the keyhole will also enable prediction of porosity and crack  susceptibility during welding. Simulation of the keyhole requires modelling of heat transfer in three dimensions while simultaneously taking into account the solid-liquid and liquid-vapour interactions. This complex phenomenon, when coupled with the small grid size and time steps required, increases the computation cost significantly. Graphical Processing Units (GPU) can significantly reduce the simulation time. [OpenCL](https://www.khronos.org/opencl/) is open source and also has cross-platform compatibility which makes the code portable. In this work, an attempt was made to model the characteristics of the keyhole during electron beam welding of beta Ti alloy using GPUs. The simulation was benchmarked with experimental studies and the difference in simulation times between CPU and GPU implementation was also quantified to understand the effect of GPU on the runtime. The effect of the electron beam radius on the keyhole was parameterised to determine the optimal processing condition.


### 4. Hot cracking susceptibility of Ni-base superalloys during laser based additive manufacturing

A multi-scale approach for formualted to predict the cracking susceptibilty of Ni-based superalloys. A macro-scale model was used to model the heat flow which predicted the cooling rates, gradients of temperature in in the domain. This was then fed into a phase field model to predict the morphological evolution of the microstructre in the soldification front.  The shape of the dendrites and the ease of fluid flow in the inter-dendritic region was used to claculate the cracking susceptibilty. All the simulaions were carried out using in-house codes.


### 5. Study on densification and grain growth characteristics during spark plasma sintering of MgO

The goal was to optimise the process conditions to obtain sintered MgO pellets with high density but minimal grain growth.  The MgO powders were annealed in a furnace at a temperature and duration enough to remove moisture but not aid grain growth.
These were then sintered under various temperatures, pressures and electric current. The sintered samples were charecterised extensively with X-Ray diffraction, SEM and density measurements. The mode of the grain growth was determined based on the growth rate. 



## Course projects

### 1. Effect of an inhomogenity on a dislocation 

The dynamics of dislocations determines the plasticity of a material. Though there are various reasons for the movement dislocations to get hindered, presence of inhomogeneity plays a very significant role. The presence of inhomogeneity can significantly hinder the dislocations thus strengthening the material. This is the mechanism by which many alloys, including Al-Cu alloys, acquire its strength. Thus, understanding the effect of inhomogeneities on dislocation would enable us to predict the mechanical response of many industrially relevant alloy systems. To understand how inhomogeneities in the matrix affect the dislocation motion, we tried to determine the force acting on the dislocation for a given strain boundary condition and compare it with the case where the material is homogeneous.


### 2. Calculation of Interfacial energies for θ′ precipitates in Al-Cu matrix

We presented a study to model the interface energies of precipitates growing in a mtrix. We implemented DFT techniques to calculate the bulk energies of Al-Cu matrix, θ′ precipitates , interface energicies of the matrix and θ′ precipitates and the energy due to the coherency strain associated with the interface. We tried to calculate all the parameters that are required by models like phase field methods to understand the microstructure evolution thus enabling a multiscale approach to solve engineering problems.



### 3. Flow in a channel with an obstacle

We developed codes to model the flow of a liquid in a channel with a solid obstacle in it.
We wrote codes in C++ to solve the Navier-Strokes equation in 2-D with appropriate boundary conditions. We implemented SIMPLE algorithm which was solved using Gauss-Siedel.

# 16S5P Lithium-Ion Battery Pack Modeling & Simulation

A MATLAB/Simulink project for modeling and simulating a 16S5P lithium-ion battery pack using Simscape Battery.

## Project Overview

This project demonstrates the configuration, modeling, and simulation of a lithium-ion battery pack consisting of 16 cells connected in series and 5 cells in parallel.

The model was developed to study pack-level electrical behavior during discharge and to monitor key battery parameters.

## Battery Configuration

| Parameter | Value |
|---|---:|
| Cell chemistry | Lithium-ion |
| Cell nominal voltage | 3.7 V |
| Cell capacity | 6 Ah |
| Series cells | 16 |
| Parallel cells | 5 |
| Configuration | 16S5P |
| Nominal pack voltage | ~59.2 V |
| Total pack capacity | 30 Ah |

## Simulation

The Simulink test model monitors:

- Battery pack voltage
- Battery current
- State of Charge (SOC)

A resistive load is used to demonstrate battery discharge behavior.

The simulation was run over an extended discharge period to observe changes in pack voltage, current, and SOC.

## Tools & Technologies

- MATLAB
- Simulink
- Simscape
- Simscape Battery
- MATLAB Battery Builder

## Project Structure

```text
MATLAB-16S5P-Battery-Pack/
├── Battery_16S5P.slx
├── Battery_16S5P_lib.slx
├── Battery_16S5P.mat
├── README.md
├── LICENSE
└── .gitignore
```

## Learning Outcomes

This project provided practical experience with:

- Battery pack configuration
- Series-parallel cell arrangement
- Simscape battery modeling
- Electrical measurement and sensing
- SOC monitoring
- Simulink-based simulation
- Interpreting battery discharge characteristics

## AI-Assisted Learning

AI tools were used as a learning and troubleshooting aid during the modeling process. The model configuration, implementation, and simulation were carried out and verified in MATLAB/Simulink.

## Author

**TrellisTrey**

B.Tech Mechatronics Engineering Student  
Parul University, India

### Areas of Interest

- EV/HEV Systems
- Battery Modeling & Simulation
- Embedded Systems

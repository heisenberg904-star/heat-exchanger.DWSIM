# Heat-Exchanger.DWSIM
Solving complex problem on heat exchanger using chemical engineering software DWSIM

![Heat Exchanger Design ](https://www.teknoflow.co/wp-content/uploads/2025/02/heat-exchanger-website.webp)

# Heat Exchanger Simulation using DWSIM

## Overview
This project involves solving a heat exchanger problem using **DWSIM**, an open-source chemical process simulator. The simulation analyzes the heat transfer between water and methanol in a counter-current heat exchanger system.

## Problem Description
The heat exchanger is designed to transfer heat between two streams:
- **Cold stream**: Water (H₂O) at **10°C** and **1 bar** pressure.
- **Hot stream**: Methanol (CH₃OH) at **80°C** and **5 bar** pressure.

### Input Stream Conditions
| Parameter              | Cold Stream (H₂O) | Hot Stream (CH₃OH) |
|------------------------|------------------|-------------------|
| **Mass Flow**         | 15000 kg/h       | 25000 kg/h       |
| **Mole Fraction CH₃OH** | 0                | 1                 |
| **Mole Fraction H₂O**  | 1                | 0                 |
| **Temperature**       | 10°C             | 80°C             |
| **Pressure**         | 1 bar            | 5 bar            |

### Heat Exchanger Properties
| Parameter                 | Value |
|---------------------------|-------|
| **Flow Type**            | Counter Current |
| **Overall HT Coefficient** | 450 W/(m².K) |
| **Heat Exchanger Area**   | 250 m² |
| **Cold Fluid Pressure Drop** | 0.002 bar |
| **Hot Fluid Pressure Drop**  | 0.025 bar |
| **Property Package**       | Raoult's Law |

## Simulation in DWSIM
### Steps to Solve in DWSIM
1. **Open DWSIM** and create a new simulation.
2. **Define the components** (Water and Methanol).
3. **Set up the property package** (Raoult's Law for phase equilibrium calculations).
4. **Specify inlet streams** with given mass flow rates, temperatures, and pressures.
5. **Insert a heat exchanger unit** and configure it for counter-current flow.
6. **Define heat transfer parameters**, including overall heat transfer coefficient and heat exchanger area.
7. **Run the simulation** and analyze the outlet temperatures, heat duty, and pressure drops.
8. **Validate results** with theoretical calculations.

## Results and Observations
- The heat exchanger effectively transfers heat from the hot methanol stream to the cold water stream.
- The simulation provides outlet temperatures, heat duty, and efficiency insights.







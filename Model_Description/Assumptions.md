# Key assumptions

This document lists the main modeling assumptions used in the Aspen Plus process model.

## Thermodynamics
- Property method: Peng–Robinson (update if different)
- Components included: CH4, H2, C2H4, (others if included)

## Reactor and process
- Steady-state operation is assumed.
- Pressure drops are neglected unless explicitly modeled.
- Heat losses are neglected unless explicitly modeled.
- Separation units are modeled as equilibrium stages or specified split fractions (update as needed).

## Data and parameter sources
- Feed composition and operating conditions are provided in `Input_Data/`.
- Reaction performance parameters (conversion/selectivity correlations or kinetic parameters) are documented in `Input_Data/` and/or manuscript/SI.

## Reproducibility note
Aspen Plus is commercial software; execution requires a valid license.
To ensure transparency, we provide complete model files, parameter tables, and representative outputs.

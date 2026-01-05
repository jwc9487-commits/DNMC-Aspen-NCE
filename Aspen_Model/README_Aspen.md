# Aspen Plus Model Description

This directory contains the Aspen Plus process model used in the Joule manuscript.

## Model files
- The main Aspen Plus backup file (`.bkp`) represents the full steady-state process model.
- The model includes feed preparation, reactor, separation, and heat integration blocks.

## Aspen configuration
- Software: Aspen Plus
- Version: v12 (or compatible)
- Property method: Peng–Robinson

## Reactor modeling approach
- The main reactor is modeled using a plug-flow reactor (RPlug).
- Methane conversion and product selectivity are implemented based on experimentally fitted correlations.
- Lumped reaction kinetics are used to represent CH₄ conversion to C₂ hydrocarbons and H₂.

## Notes on accessibility
Aspen Plus is a commercial software; therefore, execution of the model requires a valid Aspen license.
However, the full model structure, assumptions, input data, and representative outputs are provided
in this repository to ensure transparency and reproducibility.

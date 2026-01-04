# Piperacillin-dose-exposure-simulation
Simulation of Piperacillin Steady-State Concentrations Using Linear PK Assumptions
This project demonstrates a simple simulation of steady-state piperacillin
concentrations under continuous infusion using basic pharmacokinetic
assumptions.

## Related Work
This simulation builds on the dose–exposure relationship estimated in
the companion project: [piperacillin-dose-exposure-regression] https://github.com/Ketsia304/Piperacillin-Dose-Exposure-Modelling-Using-Linear-Regression?tab=readme-ov-file#piperacillin-dose-exposure-modelling-using-linear-regression

## Methods
- Clearance was simulated as a log-normally distributed parameter to ensure
  positive values and realistic variability.
- Steady-state concentration was calculated using:
  Css = infusion rate / clearance
- Simulated concentrations were visually compared with observed data.

## Notes
This simulation is exploratory and intended for educational purposes.
It does not represent a validated pharmacokinetic model.


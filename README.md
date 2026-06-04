# Quarter-Car Suspension Simulation

A Python-based simulation of a quarter-car suspension system using differential equations and numerical integration techniques.

## Overview

This project investigates vehicle suspension response to road disturbances.

The simulation solves the governing differential equations using SciPy and visualizes displacement, velocity, and acceleration responses.

## Features

- Quarter-car suspension model
- Road bump excitation
- Sinusoidal road excitation
- Numerical ODE solution
- Data visualization using Matplotlib

## Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Mathematical Model

The suspension system is modeled by:

mẍ + cẋ + k(x − r) = 0

where:

- m = vehicle mass
- c = damping coefficient
- k = spring stiffness
- r(t) = road profile input

## Repository Structure

```text
quarter-car-suspension-simulation/
│
├── README.md
├── requirements.txt
├── quarter_car_model.ipynb
├── LICENSE
└── .gitignore
```

## Future Improvements

- Half-car model
- Full vehicle model
- Active suspension control
- PID control implementation
- State-space analysis

## Author

Shinoy Antony

Physics Master's Student

Computational Physics | Vehicle Dynamics | Scientific Computing

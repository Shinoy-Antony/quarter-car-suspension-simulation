# Quarter-Car Suspension Simulation

A Python simulation of a quarter-car suspension system using differential equations and numerical methods.

## 📋 Overview

This project implements a mathematical model of a quarter-car suspension system, demonstrating how suspension components interact under various road conditions. The simulation uses differential equations to accurately represent the dynamics of the suspension system.

## 🎯 Features

- Accurate numerical modeling of suspension dynamics
- Support for various road input profiles (bumps, sinusoidal excitation)
- Real-time visualization of system behavior
- Customizable suspension parameters
- Detailed analysis of suspension performance
- Displacement, velocity, and acceleration response analysis

## 🛠️ Technology Stack

- **Language**: Python
- **Notebooks**: Jupyter Notebook
- **License**: MIT License
- **Core Dependencies**: 
  - NumPy - Numerical computing
  - SciPy - Scientific computing and ODE solving
  - Matplotlib - Data visualization

## 🚀 Getting Started

### Prerequisites

```bash
python 3.7+
pip
```

### Installation

```bash
git clone https://github.com/Shinoy-Antony/quarter-car-suspension-simulation.git
cd quarter-car-suspension-simulation
pip install -r requirements.txt
```

### Usage

```bash
jupyter notebook
# Open quarter_car_model.ipynb to run simulations
```

## 📊 Project Structure

```
quarter-car-suspension-simulation/
├── README.md
├── requirements.txt
├── quarter_car_model.ipynb
├── LICENSE
└── .gitignore
```

## 🔬 How It Works

### Mathematical Model

The quarter-car suspension system is modeled using a mass-spring-damper system governed by:

```
mẍ + cẋ + k(x − r) = 0
```

Where:
- **m** = Vehicle body mass
- **c** = Damping coefficient (shock absorber)
- **k** = Spring stiffness
- **r(t)** = Road profile input
- **x** = Vehicle displacement
- **ẋ** = Vehicle velocity
- **ẍ** = Vehicle acceleration

### Key Components

- **Vehicle Body Mass**: Upper mass of the quarter-car model
- **Suspension Spring**: Suspension stiffness determining natural frequency
- **Damper**: Shock absorber damping coefficient affecting oscillation behavior
- **Tire Characteristics**: Road input profile modeling

### Numerical Solution

The simulation uses **SciPy's ODE solvers** (odeint/solve_ivp) to numerically integrate the differential equations with:
- Runge-Kutta integration methods
- Adaptive time stepping
- Custom road excitation profiles

## 📈 Results & Visualization

The simulation provides:
- **Displacement vs. time plots** - Vehicle body motion
- **Velocity profiles** - Rate of change of displacement
- **Acceleration analysis** - Second derivative of displacement
- **Frequency response characteristics** - System natural frequency
- **Phase plane diagrams** - State space representation
- **Road input vs. vehicle response** - Comparison analysis

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs and feature requests.

## 📋 Future Improvements

- Half-car model (2 DOF system)
- Full vehicle model (4 DOF system)
- Active suspension control
- PID control implementation
- State-space analysis and transfer functions
- Optimization of suspension parameters

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Shinoy Antony**
- GitHub: [@Shinoy-Antony](https://github.com/Shinoy-Antony)
- Physics Master's Student
- Expertise: Computational Physics | Vehicle Dynamics | Scientific Computing

## 📚 References

- [Quarter-Car Suspension Model Theory](https://en.wikipedia.org/wiki/Suspension_(vehicle))
- [Numerical Methods for ODEs](https://en.wikipedia.org/wiki/Numerical_methods_for_ordinary_differential_equations)
- [Vehicle Dynamics Fundamentals](https://en.wikipedia.org/wiki/Vehicle_dynamics)

## 📞 Contact & Support

For questions or support, please open an issue on the [GitHub repository](https://github.com/Shinoy-Antony/quarter-car-suspension-simulation/issues).

---

**Last Updated**: June 4, 2026

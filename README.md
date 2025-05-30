# 🔋 Custom Battery Simulation using PyBaMM

This project uses PyBaMM to simulate a lithium-ion battery using the Single Particle Model with electrolyte (SPMe). It demonstrates how a battery behaves under a custom set of physical parameters and a realistic experiment cycle.

## 🚀 What This Project Does

- Defines a custom battery setup with unique values for thickness, particle size, conductivity, and temperature.
- Simulates a charge-discharge experiment with rest periods.
- Visualizes voltage behavior over time.
- Compares the results to a standard model to observe performance differences.

## ⚙️ Key Features

- **Battery Model**: Single Particle Model with electrolyte (SPMe)
- **Experiment Cycle**:
  - Discharge at 2C to 3.0V
  - Rest for 15 minutes
  - Charge at 1C to 4.2V
  - Hold at 4.2V until current drops to C/20
  - Rest for 10 minutes

## 📊 What You’ll See in the Results

- Voltage vs time plots from the custom simulation
- Insights about how battery parameters affect performance

## 📚 Tools Used

- PyBaMM
- NumPy
- Matplotlib

## 🧠 What I Learned

This project helped me understand how different battery parameters influence performance, and how to simulate real-world experiments using PyBaMM.


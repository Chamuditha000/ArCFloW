# ArCFloW
ArCFloW is a tool where user can add positions of a object Over Time and get trajectory Equation.

Overview

ArcFlow is a Python-based trajectory prediction and interpolation tool that utilizes numerical methods to estimate and visualize motion paths. The tool applies Lagrange interpolation, cubic spline interpolation, and divided difference interpolation to predict smooth trajectories with minimal real-world physics, including basic gravity effects.

Features

🔸 Physics-Based Trajectory Generation: Simulates projectile motion using initial velocity, launch angle, and gravity.

🔸 Lagrange Interpolation: Approximates trajectory points using polynomial interpolation.

🔸 Cubic Spline Interpolation: Smooths trajectory data for better accuracy.

🔸 Divided Difference Interpolation: Handles unevenly spaced trajectory data.

Visualization: Compares original physics-based data with interpolated results.

Installation

To run ArcFlow, install the required dependencies:

`pip install numpy matplotlib scipy`

Usage

Run the main script to generate and visualize trajectory predictions:

`python trajectory_interpolation.py`

Customize initial velocity and launch angle by modifying:

`plot_trajectory(v0=20, theta=45)`

Project Structure
```bash
ArcFlow/
│── trajectory_interpolation.py  # Main script for physics and interpolation
│── README.md                    # Project Introduction
│── Theoratical concepts.pdf     # Theory
│── code and results.pdf         # Results 
│── requirements.txt             # Dependencies
```
Future Improvements

Add air resistance modeling for more realistic physics.

Implement real-world dataset integration.

Extend to 3D trajectory predictions.





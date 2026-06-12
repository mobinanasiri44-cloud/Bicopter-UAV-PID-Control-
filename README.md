# Bicopter-UAV-PID-Control-

## Overview

This project presents the modeling, analysis, and control of a Bicopter Unmanned Aerial Vehicle (UAV). The objective was to develop a complete control framework, starting from nonlinear system dynamics and ending with closed-loop performance evaluation under realistic operating conditions.

The project includes nonlinear modeling, system linearization, transfer function derivation, PID controller design, and robustness analysis against external disturbances and measurement noise. All simulations and controller validations were performed using MATLAB/Simulink.

---

## Project Objectives

The following objectives were addressed throughout the project:

* Develop a nonlinear dynamic model of a Bicopter UAV
* Linearize the nonlinear model around an equilibrium operating point
* Derive the corresponding transfer functions
* Define appropriate control performance specifications
* Design and tune PID controllers
* Evaluate closed-loop performance
* Investigate the effect of external disturbances
* Analyze system behavior in the presence of measurement noise
* Validate controller performance on both linearized and nonlinear models

---

## System Modeling

A nonlinear dynamic model of the bicopter was developed based on its physical dynamics and motion equations.

The model captures the relationship between rotor-generated forces and the resulting translational and rotational motion of the vehicle.

### Nonlinear Model

---

## System Linearization

To facilitate controller design and analysis, the nonlinear system was linearized around an operating point.

The resulting linear model was used for transfer function derivation and PID controller design.

### Linearized Model

---

## Controller Design

A PID-based control strategy was developed to stabilize the bicopter and achieve the desired dynamic performance.

The controller parameters were selected through analysis and simulation to achieve:

* Stable closed-loop behavior
* Acceptable transient response
* Reduced steady-state error
* Improved disturbance rejection capability

The controller was first validated on the linearized model and subsequently applied to the nonlinear system.

---

## Simulation Results

The designed controller was evaluated through extensive MATLAB/Simulink simulations.

### Closed-Loop Response

The system successfully achieved stable tracking behavior while maintaining satisfactory transient performance.

### Attitude Response

The controller provided effective stabilization of the bicopter dynamics.

---

## Disturbance Rejection Analysis

External disturbances were introduced to evaluate controller robustness.

Simulation results demonstrate that the controller can maintain stability and recover from disturbances within an acceptable time interval.

---

## Noise Analysis

Measurement noise was incorporated into the simulation environment to investigate controller sensitivity.

The control system maintained acceptable performance despite the presence of measurement noise.

---

## Software and Tools

* MATLAB
* Simulink
* Control System Toolbox

---

## Repository Structure

```text
models/ : Nonlinear and linearized bicopter model diagrams
closed_loop/ : Closed-loop control architectures with PID controllers, disturbances, and measurement noise
simulation/ : Nominal response, disturbance rejection, and noise analysis results
report/ : Final project report
files/ : Simulink implementation file (.slx)
```

---

## Key Outcomes

* Developed a nonlinear mathematical model of a Bicopter UAV
* Performed system linearization and transfer function derivation
* Designed and tuned PID controllers
* Evaluated closed-loop performance through simulation
* Analyzed disturbance rejection and noise sensitivity
* Validated controller performance on both linearized and nonlinear models

---

## Academic Context

This project was completed as the final project for Linear Control Systems course prisented by Prof. Heidarali Talebi in the Electrical Engineering (Control Engineering) program.

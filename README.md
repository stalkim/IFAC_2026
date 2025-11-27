# Coordinated Path Following Control for Quadrotor UAV

This repository contains supplementary materials for the paper **"Coordinated Path Following Control for Quadrotor UAV Based on Enhanced Extended State Observer"**, submitted to **IFAC 2026**.

The project demonstrates a robust control framework that decouples geometric path convergence from temporal progression, enabling precise tracking under parametric uncertainties.

## Simulation Results

Below are the animated visualizations of the proposed control law performance in two test scenarios.

### 1. Line Path Scenario
The quadrotor follows a straight-line trajectory. The animation shows convergence to the path with independent speed regulation.

![Line Path Animation](Line.gif)

### 2. Spring (Helix) Path Scenario
A complex 3D helix trajectory ("Spring") requiring simultaneous coordination of all three spatial coordinates.

![Spring Path Animation](Spring.gif)

## Abstract
This paper addresses the coordinated path following control problem for a quadrotor UAV under parametric uncertainties and external disturbances. The coordinated control framework decouples geometric path convergence from temporal constraints, enabling independent speed regulation along the path. An enhanced extended state observer reconstructs unmeasured velocity states and compensates for lumped disturbances.

---
**Authors:** Stanislav Kim, Anton Pyrkin, Oleg Borisov  
**Affiliation:** ITMO University, Saint Petersburg, Russia

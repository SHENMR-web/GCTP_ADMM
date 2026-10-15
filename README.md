# GCTP-ADMM

### Geometrically-Constrained Trajectory Planning for Multi-UAV in Shared Corridors

> [!IMPORTANT]
> **THE SOURCE CODE WILL BE RELEASED AFTER THE PAPER IS PUBLISHED.**
>
> The manuscript is currently under peer review. This repository provides supplementary simulation videos.

## Overview

Our research studies how multiple quadrotors can navigate narrow, shared safe flight corridors while accounting for the shape and attitude of each vehicle. In these environments, clearance depends on the full rotating UAV body as well as its center trajectory.

We propose **Geometrically-Constrained Trajectory Planning with ADMM (GCTP-ADMM)**, a framework that combines piecewise Bézier trajectories with an attitude-dependent convex polyhedral model of each UAV. Support functions describe body-to-corridor clearance, dual separation certificates model inter-UAV separation, and local convex dynamics models account for flight limits. The alternating direction method of multipliers (ADMM) decomposes the trajectory and separation-certificate updates into tractable convex subproblems.

## Simulation Videos

The following simulations illustrate three traffic patterns. Colored bodies represent UAVs, colored curves show their trajectories, translucent red regions show safe flight corridors, and gray structures show the surrounding obstacles.

### 1. One-Way Maze — 5 UAVs

Five UAVs traverse a shared corridor chain through a maze in the same direction.

https://github.com/user-attachments/assets/4c783664-a49d-455b-90cd-9538f5ba6258

### 2. Two-Way Maze — 6 UAVs

Six UAVs travel through the shared maze corridors in opposing directions.

https://github.com/user-attachments/assets/c5586bd9-d08a-4b33-b6a7-6a7f86cb6bd3

### 3. Crossing Paths — 8 UAVs

Eight UAVs follow crossing trajectories inside a hexagonal-prism environment.

https://github.com/user-attachments/assets/c49ccdb9-eab4-41eb-88b0-ed6775c6108e

## Code Availability

**The source code will be made publicly available in this repository after the paper is published.**

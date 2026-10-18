# modeling-and-simulation-matlab
Modeling and simulation of dynamic systems using MATLAB and Simulink — TU Dresden team project

Modeling and Simulation — MATLAB / Simulink
TU Dresden | Summer Semester 2026 | Team Project
This repository documents a group laboratory project completed as part of Elemente der Modellbildung und Simulationstechnik (Elements of Modeling and Simulation Technology) at Technische Universität Dresden.
The laboratory consisted of three assignments focused on numerical simulation, nonlinear and hybrid dynamic systems, and differential-algebraic equations (DAEs). The work was carried out in a four-person team using MATLAB and Simulink.
Laboratory assignments

1. Numerical Integration and Nonlinear Simulation
The first assignment explored numerical simulation algorithms and their application to dynamical systems:
- Simulation of a first-order (PT1) system under a step input.
- Improved polygonal integration method (Verbesserte Polygonzugmethode, VPG), with local discretization error estimation.
- Adaptive integration step-size control and verification against a known response.
- Block-oriented simulation of a nonlinear pseudorate modulator with hysteresis and discontinuities.
  
2. Modeling and Control of a Servohydraulic System
The second assignment concerned a nonlinear hybrid system representing a servohydraulic force-testing apparatus, with a motivating application in aircraft wing structural testing.
Key topics included:
- Continuous-time modeling and simulation with MATLAB/Simulink.
- Discrete-time modeling using a state-transition matrix.
- Modeling nonlinear elements and measurement delay.
- Analysis of a feedback system with integral control.
  
3. Numerical Integration of DAE Systems
The third assignment concerned the numerical simulation of an RC electrical network represented as a semi-explicit differential-algebraic equation (DAE) system.
Key topics included:
- Formulating a semi-explicit DAE model and analyzing its differential index.
- Implementing implicit trapezoidal integration with Newton–Raphson iterations.
- Computing and using an analytical Jacobian matrix.
- Investigating numerical accuracy using single-precision floating-point arithmetic.
  
Tools and concepts
- Tools: MATLAB, Simulink, Git
- Methods: numerical integration, adaptive step-size control, Newton–Raphson, Jacobian matrices
- Systems: nonlinear and hybrid dynamical systems, feedback control, DAE models
  
Teamwork and source code
This was a collaborative academic project, not an individual software project. The descriptions above summarize the laboratory assignments; they are not a claim that I implemented every component personally.
The original group repositories are maintained separately. For reference:

[Original group repository — ModSim Praktikum](https://github.com/lukanna04/ModSim_Praktikum)

The complete group source code is not redistributed here. This repository serves as a technical overview of the work undertaken during the course.
Academic context
- University: Technische Universität Dresden
- Course: Elemente der Modellbildung und Simulationstechnik (MODSIM)
- Term: Summer Semester 2026
- Format: Three MATLAB/Simulink laboratory assignments completed in a four-person team
Documentation based on the official SS 2026 laboratory assignment sheets. Specific individual contributions and implementation results can be added after verification against the project files.

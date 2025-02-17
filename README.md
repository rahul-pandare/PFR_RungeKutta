# Solving Mass Balance Differential Equations for an Isothermal Plug Flow Reactor Using the Runge-Kutta Method  

## Overview  
This repository contains a numerical approach for solving mass balance differential equations governing an **isothermal Plug Flow Reactor (PFR)** using the **Runge-Kutta method**. The reaction kinetics follow the **Langmuir-Hinshelwood mechanism**, which accounts for adsorption effects on catalytic surfaces.  

## Methodology  
- The reactor model is formulated as an **Ordinary Differential Equation (ODE)** based on material balance considerations.  
- The **Runge-Kutta method** is employed to integrate the differential equation, providing a numerical solution for the concentration profile along the reactor length.  
- The algorithm computes the **outlet concentration of reactants**, enabling performance analysis for an ideal PFR.  

## Features  
- Implementation of **Runge-Kutta (RK4) numerical integration** for solving PFR mass balance equations.  
- **Isothermal conditions** assumed for simplification.  
- **Langmuir-Hinshelwood kinetics** incorporated to model catalytic reactions.  
- Suitable for undergraduate **chemical engineering** projects and process simulations.  

## Usage  
1. Ensure **Python** and required dependencies (NumPy, SciPy, Matplotlib) are installed.  
2. Run the provided Jupyter Notebook to execute the calculations.  
3. Modify parameters such as reaction rate constants, adsorption coefficients, and reactor length for different case studies.  

## Requirements  
- Python (Recommended: 3.x)  
- Jupyter Notebook  
- NumPy, SciPy, Matplotlib  

This repository serves as a useful tool for understanding **reactor design principles** and applying **numerical methods** to solve chemical engineering problems.  

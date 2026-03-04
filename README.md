# BioServer: Cardiovascular Dynamics & Parameter Estimation

BioServer is a high-fidelity computational framework developed in **MATLAB** for human hemodynamic simulation and non-invasive vascular phenotyping.

By leveraging 3-element Windkessel lumped parameter models, the system translates complex physiological signals into actionable clinical biomarkers, acting as a **Vascular Digital Twin**.

## Key Features

* **Biophysical Modeling:** Accurate resolution of differential equations to characterize systemic arterial impedance and the Windkessel effect.
* **Numerical Optimization Engine:** Robust identification of physiological parameters (arterial compliance and peripheral resistance) using non-linear least-squares algorithms.
* **Interactive Simulation:** A custom-built GUI (Graphical User Interface) for real-time manipulation of clinical variables and pathological scenario modeling.

## Clinical Innovation

The framework enables the quantification of arterial stiffness and the simulation of specific pathologies, such as **Hypertension**, **Arteriosclerosis**, and **Aortic Stenosis**, in a risk-free virtual environment. This predictive approach supports clinical decision-making by identifying vascular phenotypes that typically require invasive assessment.

## Technical Implementation

* **Core Engine:** MATLAB ODE Solvers (e.g., `ode45`).
* **Optimization:** Parametric estimation via `lsqnonlin` and gradient-based methods.
* **Interface:** MATLAB App Designer.

*Developed as part of a Bioengineering research initiative focusing on Hemodynamics and Systems Identification.*

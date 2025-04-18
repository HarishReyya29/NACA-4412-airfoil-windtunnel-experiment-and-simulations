# NACA-4412-airfoil-wind-tunnel-experiment-and-simulations
This project investigates the aerodynamic performance of the NACA 4412 airfoil through both wind tunnel experiments and numerical simulations. It provides a hands-on comparison between experimental data and CFD results for validating airfoil lift, drag, and flow behavior over a range of angles of attack.

🧪 Wind Tunnel Testing
Conducted subsonic wind tunnel tests using a NACA 4412 model.

Measured lift, drag, and moment coefficients.

Collected pressure distribution over the airfoil surface using pressure taps.

Analyzed boundary layer behavior and stall characteristics.

💻 CFD Simulations
Simulated steady-state, incompressible flow using RANS models (k-ε / k-ω SST).

Modeled external flow using structured mesh around the airfoil.

Performed angle of attack sweep to observe lift curve slope and stall onset.

Compared numerical Cp distribution with experimental results.

📊 Outcomes
Good agreement between wind tunnel data and CFD up to pre-stall conditions.

Cp plots, lift-drag polars, and boundary layer visualization.

Analysis of discrepancies due to wall effects, transition, and turbulence modeling.

🧰 Tools & Software
Wind Tunnel Facility (Lab-based)

ANSYS Fluent / OpenFOAM for CFD

MATLAB / Python for data processing and plotting

📁 Folder Structure
/experiment_data: Raw wind tunnel measurements and processed plots

/CFD_simulations: Mesh files, solver setup, and post-processing scripts

/plots: Comparison plots of Cp, CL vs AoA, CD vs AoA, etc.

# Biomechanical Analysis: The Mathematics of Safe Lifting

## Overview
This project explores the mathematical and physical principles governing human lifting mechanics. By utilizing biomechanical leverage models, the study analyzes the forces acting on the human musculoskeletal system, specifically focusing on the compression forces exerted on the L5/S1 lumbosacral joint(lower back) during the lifting process.

## Project Objectives
*   Formulate a mathematical model representing the human torso as a Class 1 Lever system.
*   Quantify the relationship between torso inclination angles, load distance, and resultant spinal compression.
*   Develop a Python-based simulation within a Jupyter Notebook to visualize how vertebral pressure scales with varying postures.
*   Present a data-driven tutorial on injury prevention based on numerical evidence and static equilibrium.

## Problem Formulation and Significance
Biomechanical research indicates that a significant portion of occupational back injuries result from excessive torque applied to the lower spine. 
*   **The Mechanical Challenge:** When an individual lifts an object, both the weight of the upper body (trunk) and the external load create a moment arm relative to the spinal pivot point. 
*   **Mathematical Context:** To maintain static equilibrium, the posterior muscles must exert significant tension. This internal force, combined with the external load, translates into substantial compression on the intervertebral discs. Understanding this relationship is critical for developing ergonomically sound lifting protocols.

## Technical Framework
*   **Language:** Python 3.x
*   **Environment:** Jupyter Notebook
*   **Libraries:** NumPy (Trigonometric modeling), Data visualization....?

## References
*   [California State University, Chico - Lifting Techniques (PDF)](https://www.csuchico.edu/ehs/_assets/documents/lifting-techniques.pdf)
*   [University of Waterloo - Biomechanical Analysis of Lifting (DSpace)](https://dspacemainprd01.lib.uwaterloo.ca/server/api/core/bitstreams/bad0b630-72d1-46cc-b5cd-393c18dbf902/content)
*   [National Institute for Occupational Safety and Health(NIOSH)](https://www.cdc.gov/niosh/index.html)
*   [The NIOSH Lifting Equation for Manual Lifting](https://www.longdom.org/open-access/the-niosh-lifting-equation-for-manual-lifting-and-its-applications-23286.html)

## Installation and Execution
1. Clone the repository to a local machine.
2. Ensure the required dependencies are installed via `pip install -r requirements.txt`.
3. Execute the `Safe_Lifting_Analysis.ipynb` notebook to review the mathematical derivations and simulation results.


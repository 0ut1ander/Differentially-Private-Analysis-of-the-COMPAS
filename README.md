# Differentially-Private-Analysis-of-the-COMPAS
Differentially private analysis of COMPAS criminal justice data using Laplace and Gaussian mechanisms - CIS 545 group project, UM-Dearborn.

This repository contains a group project for CIS 545 at University of Michigan–Dearborn. We performed a differentially private analysis on the COMPAS criminal justice dataset using Laplace and Gaussian noise mechanisms.

## Files Included
- `CIS_545_Project_Notebook.ipynb`: The main Jupyter notebook. Contains all code, analysis, and data visualizations.
- `CIS_545_Project_Report.pdf`: The final written report summarizing our methods, results, and findings.
- `compas-scores-two-years.csv`: Used for our analysis. Source: (link: https://github.com/propublica/compas-analysis)

## Contributors
- **Anthony Lewis** (UM-Dearborn) – alewi@umich.edu
- **Lincoln Badejo** (UM-Dearborn) – lbadejo@umich.edu
- **Loren Fang** (UM-Dearborn) – fangxy@umich.edu
- **Margil Funtanilla** (UM-Dearborn) – mfuntanilla@umich.edu
- **Tom Tooma** (UM-Dearborn) – ttooma@umich.edu

## Personal Contribution

- Developed and implemented Python code for applying differential privacy to COMPAS dataset queries using Laplace and Gaussian mechanisms.
- Created core analysis and visualization for the following aspects:
    - Racial group distribution with privacy-preserving mechanisms (original, Laplace, Gaussian).
    - Age and gender distributions under different privacy budgets.
    - Calculation and comparison of average COMPAS risk scores (original and noise-added).
    - Computation and visualization of two-year recidivism rates (base and differentially private values).
    - Analysis of mean COMPAS score differences between Black and White defendants, demonstrating fairness impacts under differential privacy.
- Automated the comparison and reporting of results for multiple privacy settings (epsilon sweeps), and generated summary tables and privacy-utility tradeoff plots.
- Interpreted and integrated technical findings for use in group report (collaborated on experimental evaluation/results section).

## How to Run
1. Install required packages:  
   `pip install jupyter numpy pandas matplotlib`
2. Place all files in the same folder.
3. `jupyter notebook` and open `CIS_545_Project_Notebook.ipynb`
4. Run all cells for results.

## Data Availability
Download it from the this github link (https://github.com/propublica/compas-analysis).

## Project Origin
This work was completed for CIS 545 in Fall 2025 at UM-Dearborn. It is for educational use only.

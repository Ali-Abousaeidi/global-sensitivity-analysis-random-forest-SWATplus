# Global Sensitivity Analysis Using Random Forest: An Application to SWAT+

This repository contains all resources for the research article:

**Title:** Global Sensitivity Analysis of Complex Numerical Models Using Random Forest: An Application to SWAT+  
**Authors:** Ali Abousaeidi, Seyed Mohammad Mahdi Moezzi, Farkhondeh Khorashadi Zadeh, Razi Sheikholeslami, Albert Nkwasa, Paul Munoz, and Ann van Griensven  

---

## Repository Contents

- **`data/`**: Contains the datasets used in the study (e.g., meteorological data and SWAT+ outputs).
- **`code/`**: Contains scripts and Jupyter Notebooks for Random Forest-based GSA.
- **`README.md`**: Overview of the project.
- **`data/README.md`**: Detailed descriptions of datasets.
- **`code/README.md`**: Instructions for using the code.

---

## Study Overview

This study applies a Random Forest-based surrogate model to perform Global Sensitivity Analysis (GSA) on the SWAT+ model. The GSA identifies and ranks the most influential input variables for simulating river flow and sediment load in the Simiyu River Basin, Tanzania.

Key features of the study:
- **Case Study**: Simiyu River Basin, located in Southeast Lake Victoria, Tanzania.
- **Data Period**: January 1, 1952 – December 1, 2019 (monthly resolution).
- **Key Methods**:
  - Permutation Variable Importance (PVI) measures.
  - Partial Dependence Plots (PDPs).

---

## How to Use This Repository

1. Clone this repository:
   ```bash
   git clone https://github.com/Ali-Abousaeidi/global-sensitivity-analysis-random-forest-SWATplus.git

---

## License
The source code in this folder is licensed under the MIT License. See `LICENSE` file for more details.

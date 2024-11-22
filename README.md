# Global Sensitivity Analysis Using Random Forest: An Application to SWAT+

This repository contains the dataset used in the research study:

**Title:** Global sensitivity analysis of complex numerical models using Random Forest: An application to SWAT+  
**Authors:** Ali Abousaeidi, Seyed Mohammad Mahdi Moezzi, Farkhondeh Khorashadi Zadeh, Razi Sheikholeslami, Albert Nkwasa, Paul Munoz and Ann van Griensven 

---

### Data Files
- Monthly.xlsx: Includes all input variables (e.g., precipitation, temperature, wind speed, solar radiation, and humidity) used in the study.
- simiyu_similuations_swat+.xlsx: Includes the simulated river flow and sediment load data generated using the SWAT+ model.

---

## Case Study Description
The dataset corresponds to the **Simiyu River Basin**, located in Southeast Lake Victoria, Tanzania. Key features of the study area include:
- **Location:** Simiyu River Basin (33.75°E to 34.75°E and 2.75°S to 3.25°S).
- **Data Period:** January 1, 1952, to December 1, 2019 (monthly resolution).
- **Climate and Hydrology:** The basin experiences a tropical savannah climate, with precipitation ranging from 700–800 mm annually and average temperatures of 23°C. River discharge patterns align with seasonal rainfall, with higher flows during the long rainy season (March to May).  

---

### Input Variables
The dataset includes meteorological inputs and other SWAT+ model parameters, as described below:

| **Variable**          | **Description**                               | **Range**          |
|------------------------|-----------------------------------------------|--------------------|
| `Prec-S-1` to `Prec-S-6` | Monthly precipitation at 6 stations [mm]     | 0–540.5            |
| `Prec-Ave-1` to `Prec-Ave-6` | Monthly average precipitation at 6 stations [mm] | 0–17.4            |
| `Wind-1` to `Wind-6`  | Monthly average wind speed at 6 stations [m/s]| 1.288–5.29         |
| `Temp-Max-1` to `Temp-Max-6` | Monthly average max temperature [°C]     | 24–31.5            |
| `Temp-Min-1` to `Temp-Min-6` | Monthly average min temperature [°C]     | 12–20              |
| `Solar-1` to `Solar-6` | Monthly average solar radiation [W/m²]       | 27.4–33.3          |
| `Hum-1` to `Hum-6`    | Monthly average humidity at 6 stations [%]   | 0.364–0.882        |

### Output Variables
- `Flow`: Monthly average SWAT+ flow simulations [m³/s].
- `Sediment`: Monthly average SWAT+ sediment simulations [M ton/month].

---

## Usage
The dataset can be used to:
1. Reproduce the Random Forest-based global sensitivity analysis (GSA).
2. Develop surrogate models for SWAT+ flow and sediment simulations.
3. Perform further hydrological and sensitivity studies.

### Instructions:
1. Clone this repository or download the data as a `.zip` file:
   ```bash
   git clone https://github.com/Ali-Abousaeidi/global-sensitivity-analysis-random-forest-SWATplus.git

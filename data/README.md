
```markdown
# Dataset for Global Sensitivity Analysis Using Random Forest

This folder contains the datasets used in the study. The datasets include meteorological inputs and SWAT+ outputs for simulating flow and sediment load in the Simiyu River Basin, Tanzania.

---

## Files

- **`Monthly.xlsx`**: Contains meteorological inputs, including precipitation, temperature, wind speed, solar radiation, and humidity.
- **`simiyu_similuations_swat+.xlsx`**: Contains simulated river flow and sediment load data generated using the SWAT+ model.

---

## Variable Descriptions

| **Variable**          | **Description**                               | **Range**          |
|------------------------|-----------------------------------------------|--------------------|
| `Prec-S-1` to `Prec-S-6` | Monthly precipitation at 6 stations [mm]     | 0–540.5            |
| `Prec-Ave-1` to `Prec-Ave-6` | Monthly average precipitation at 6 stations [mm] | 0–17.4            |
| `Wind-1` to `Wind-6`  | Monthly average wind speed at 6 stations [m/s]| 1.288–5.29         |
| `Temp-Max-1` to `Temp-Max-6` | Monthly average max temperature [°C]     | 24–31.5            |
| `Temp-Min-1` to `Temp-Min-6` | Monthly average min temperature [°C]     | 12–20              |
| `Solar-1` to `Solar-6` | Monthly average solar radiation [W/m²]       | 27.4–33.3          |
| `Hum-1` to `Hum-6`    | Monthly average humidity at 6 stations [%]   | 0.364–0.882        |

---

## Output Variables

- **`Flow`**: Monthly average SWAT+ flow simulations [m³/s].
- **`Sediment`**: Monthly average SWAT+ sediment simulations [M ton/month].


# 1. Project Overview
This dataset simulates a **waterflooding strategy** for the **Neptune Selatan Oilfield**. It is configured as a three-phase model (Oil, Water, and Gas) using metric units. The simulation begins on **January 1, 2026**, and runs through mid-2042.

## 2. Model Specifications
* **Grid Dimensions**: 19 x 28 x 5 (Total of 2,660 cells).
* **Fluids**: Oil, Water, and Gas.
* **Key Property Includes**:
    * Porosity and Permeability data.
    * Corner point geometry.
* **Initial Conditions**: 
    * **Datum Depth**: 2355.0 m.
    * **Datum Pressure**: 234.46 bar.
    * **Oil-Water Contact (OWC)**: 2395.0 m.

## 3. Well Configuration
The simulation manages two primary groups of wells located in Group 'G1':

| Well Type | Well Names | Control Strategy |
| :--- | :--- | :--- |
| **Producers** | PRO-1, PRO-4, PRO-5, PRO-11, PRO-12, PRO-15 | Controlled by Oil Rate (ORAT) with a 0.9 Water Cut shut-in limit. |
| **Injectors** | INJ-1, INJ-2, INJ-3, INJ-4 | Controlled by Water Injection Rate (500 m³/day per well). |

## 4. Production Schedule Highlights
* **Initial Production (2026)**: Producers start at 200 m³/day, stepping down to 100 m³/day and then 50 m³/day through the first year.
* **Pressure Maintenance**: Continuous water injection at 500 m³/day per well to support reservoir pressure.
* **Cyclic Operation (2031–2042)**: The schedule features a repeated pattern of shutting in producers for the first 15 days of every year (likely for buildup testing or workover simulation) followed by production at 150 m³/day.

---

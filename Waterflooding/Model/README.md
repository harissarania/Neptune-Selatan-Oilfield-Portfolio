# README: Neptune Selatan Oilfield Waterflood Simulation

This README provides an overview of the Eclipse reservoir simulation dataset for the Neptune Selatan Oilfield.

---

## 1. Project Overview
[cite_start]This dataset simulates a **waterflooding strategy** for the **Neptune Selatan Oilfield**[cite: 1]. [cite_start]It is configured as a three-phase model (Oil, Water, and Gas) using metric units[cite: 1]. [cite_start]The simulation begins on **January 1, 2026**, and runs through mid-2042[cite: 1, 107, 108].

## 2. Model Specifications
* [cite_start]**Grid Dimensions**: 19 x 28 x 5 (Total of 2,660 cells)[cite: 1].
* [cite_start]**Fluids**: Oil, Water, and Gas[cite: 1].
* **Key Property Includes**:
    * [cite_start]`PUNQS3.PRP`: Porosity and Permeability data[cite: 1].
    * [cite_start]`PUNQS3.GEO`: Corner point geometry[cite: 1].
* **Initial Conditions**: 
    * [cite_start]**Datum Depth**: 2355.0 m[cite: 63].
    * [cite_start]**Datum Pressure**: 234.46 bar[cite: 63].
    * [cite_start]**Oil-Water Contact (OWC)**: 2395.0 m[cite: 63].

## 3. Well Configuration
[cite_start]The simulation manages two primary groups of wells located in Group 'G1'[cite: 66, 67, 68, 69]:

| Well Type | Well Names | Control Strategy |
| :--- | :--- | :--- |
| **Producers** | PRO-1, PRO-4, PRO-5, PRO-11, PRO-12, PRO-15 | [cite_start]Controlled by Oil Rate (ORAT) with a 0.9 Water Cut shut-in limit[cite: 66, 75, 78, 80, 82]. |
| **Injectors** | INJ-1, INJ-2, INJ-3, INJ-4 | [cite_start]Controlled by Water Injection Rate (500 m³/day per well)[cite: 69, 70, 75, 77]. |

## 4. Production Schedule Highlights
* [cite_start]**Initial Production (2026)**: Producers start at 200 m³/day [cite: 78][cite_start], stepping down to 100 m³/day [cite: 79, 80] [cite_start]and then 50 m³/day [cite: 81, 82] through the first year.
* [cite_start]**Pressure Maintenance**: Continuous water injection at 500 m³/day per well to support reservoir pressure[cite: 75, 77].
* [cite_start]**Cyclic Operation (2031–2042)**: The schedule features a repeated pattern of shutting in producers for the first 15 days of every year (likely for buildup testing or workover simulation) followed by production at 150 m³/day[cite: 87, 88, 89, 90, 91, 92, 94, 96, 99, 101, 103, 106, 108].

---

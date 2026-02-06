
##  Model Overview
* **Field Name:** Neptune Selatan Oilfield
* **Simulator:** ECLIPSE (Black Oil Model) 
* **Grid Dimensions:** $19 \times 28 \times 5$ (Total 2,660 cells) 
* **Fluids:** Oil, Water, and Gas 
* **Units:** METRIC 
* **Start Date:** 01 January 2026 

##  Reservoir Properties
The model incorporates the following key geological and fluid characteristics:
* **Grid & Permeability:** Geometry and property data (PORO, PERMX, PERMZ) are included via external files `PUNQS3.GEO` and `PUNQS3.PRP`.
* **PVT Data:** Detailed tables for dead oil (PVTO), dry gas (PVDG), and water (PVTW).
* **Rock Compressibility:** Set at $0.00045$ bar⁻¹ at a reference pressure of $235$ bar.
* **Equilibrium:** Initial reservoir pressure of $234.46$ bar at a datum depth of $2355.0$ m. The Oil-Water Contact (OWC) is set at $2395.0$ m.

##  Well Specifications
The model includes six active production wells:
* **Wells:** `PRO-1`, `PRO-4`, `PRO-5`, `PRO-11`, `PRO-12`, and `PRO-15`.
* **Control:** Wells are controlled primarily by Oil Rate (ORAT) with a Bottom Hole Pressure (BHP) limit of $120$ bar.
* **Skin Factor:** All active wells are configured with a skin factor of $5.0$.

##  Production Schedule & Strategy
The simulation covers a timeline from **2026 to 2042** with the following phases:
1.  **Initial Ramping:** Starts at $100$ SM³/d per well, increasing to $200$ SM³/d.
2.  **Depletion Phase:** Rates are stepped down to $100$ SM³/d and then $50$ SM³/d as the reservoir pressure declines.
3.  **Pressure Buildup Test:** A long-term shut-in period occurs between **2027 and 2030** for buildup analysis.
4.  **Workover Cycles:** From 2031 onwards, the field undergoes annual maintenance cycles:
    * **January 1st:** Wells are shut in (Rate = $0$).
    * **January 15th:** Wells resume production at $150$ SM³/d.

## Summary Output
The model is configured to track the following parameters:
* **Field Totals:** FOPT (Oil Production Total), FGPT (Gas), FWPT (Water).
* **Well Specifics:** Oil production rates (WOPR), Bottom hole pressure (WBHP), Gas-Oil Ratio (WGOR), and Water Cut (WWCT).

---
**Note:** Ensure the include files (`PUNQS3.PRP` and `PUNQS3.GEO`) are present in the working directory before running the simulation.

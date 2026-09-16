# Solar Mini-grid Design for Rajapuri Village — A Multidimensional Approach

Course project report for **TD619: Energy Policy and Planning**, Indian Institute of Technology Bombay (April 2025), prepared under the guidance of Prof. Anand B. Rao, Centre for Technology Alternatives for Rural Areas (C-TARA).

**Authors:** Arrunraaj K, Yash Bhongade, Yaswanth B, Ravneet Singh

## Overview

The report designs a solar PV mini-grid for an unelectrified/grid-deficient community in **Rajapuri village, Thane district, Maharashtra**, and evaluates it across technical, economic, social, institutional and environmental dimensions rather than sizing alone.

## Contents

1. **Introduction** — context on rural electrification and the case for solar over wind/diesel alternatives
2. **Techno-Economic Design**
   - Load analysis using 2019 hourly consumption data (chosen as the first stable year post-installation)
   - System sizing: solar panel, battery and inverter capacity, based on capacity factor, depth of discharge and battery efficiency assumptions
   - Levelized cost of electricity via present-value / equivalent-annual-cost analysis
   - Cross-check against a HOMER Pro simulation and the existing installed system
3. **Social Dimension** — quality of life, education, livelihoods, healthcare impacts; community engagement, tariff transparency, gender inclusion
4. **Institutional Dimension** — policy support, local governance (Village Energy Committees), partnerships, capacity building, and implementation challenges
5. **Environmental Dimension** — lifecycle impacts of energy source choice, environmental impact assessments, battery disposal and circular-economy practices
6. **Conclusion & Recommendations** — adaptive sizing, community "Energy Champion" training, e-waste management, IoT-based monitoring, and replicability for other villages

## Key results

| Parameter | Existing System | Manual Design | HOMER Pro |
|---|---|---|---|
| Solar panel capacity | 6.08 kW | 5.2 kW | 10.4 kW |
| Battery capacity | 16 kWh | 11.5 kWh | 22 kWh |
| Inverter capacity | 3 kW | 1 kW | 1.12 kW |

The manual design meets peak load at lower capital cost (LCOE ≈ ₹5.82/kWh), while HOMER Pro's higher-capacity design trades higher upfront cost for greater reliability against real weather variability.

## Tools used

- Python for load-data analysis and plotting
- HOMER Pro for techno-economic simulation and optimization

## File

`Solar_Mini-grid_Design.pdf` — full report (12 pages, incl. references and team contribution breakdown)

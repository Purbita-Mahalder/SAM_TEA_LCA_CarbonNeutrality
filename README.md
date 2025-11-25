# SAM_TEA_LCA_CarbonNeutrality
Title: Techno-Economic & Environmental Evaluation of Solar–Biomass Fuel Switching of Local Industry to Attain Carbon Neutrality Using SAM and LCA Frameworks 
 
  2 Summery: This study evaluates renewable energy solutions for decarbonizing small rice mills in Bangladesh, focusing on photovoltaic (PV), biomass, and hybrid (PV/biomass) systems compared against a grid-only baseline. Hourly load data, regional cost figures, and realistic performance parameters were used to model each configuration in the System Advisor Model (SAM). Key metrics included annual load coverage, levelized cost of energy (LCOE), and operational CO₂ emissions. Results show that the hybrid system (40% PV/60% biomass) delivers the most robust performance, achieving 96% average annual load coverage and a 96% reduction in CO₂ emissions compared to grid-only, while maintaining competitive LCOE values. PV-only and biomass-only systems each reach >94% decarbonization, though with greater seasonal dependence. These findings highlight the technical and environmental viability of hybrid renewable solutions for Bangladesh’s rural industries and support the sector’s alignment with national decarbonization and sustainability targets.
   
    3. Repository Structure:
/sam_models
   → TEA_Rice mill.sam
/data
   → solar_resource.csv
   → Electric Load Demand.csv
/results
   → SAM_TEA_all data.csv
   → Energy Demand_vs_Biomass.bmp
   → Energy Demand_vs_PV.bmp
   → Energy Demand_vs_hybrid.bmp
   → lcoh_comparison.bmp
   → CO2_emission_reduction.bmp
/report
   → SAM_TEA_LCA_CarbonNeutrality.pdf

4. Workflow Overview
Step 1 — Data Preparation

Hourly electrical load (rice mill).

Biomass availability (rice husk) and heating value.

Solar resource data (TMY, NSRDB, or local dataset).

Economic assumptions (CAPEX, OPEX, replacement costs).

Emissions factors for grid and biomass combustion.

Step 2 — System Advisor Model (SAM) Configuration

Each scenario uses:

Weather file

Electrical load

Technology configuration (PV, Biomass CHP, Hybrid)

Dispatch strategy

Financial model (industrial, single-owner)

Step 3 — Technical & Financial Evaluation

For each configuration:

Annual AC generation

Performance ratio & loss diagram

Net system output

Unmet load

Fuel consumption (biomass)

LCOE (nominal + real)

Step 4 — Environmental Assessment

Grid baseline emissions

Emissions avoided

Biomass combustion emissions

Net lifecycle impact (qualitative when needed)

Step 5 — Reporting

Outputs saved to /results/

5. Data Sources

Local rice mill hourly load (Personal Inquiry)

Solar resource DB ( National Solar Radiation Database (NSRDB))

Biomass fuel data (rice husk heating value, Cow dung heating value)

6. Citation

If you use this repository or the results: Mahalder, P. (2025). Techno-Economic & Environmental Evaluation of Solar–Biomass Fuel Switching of Local Industry to Attain Carbon Neutrality Using SAM and LCA Frameworks .



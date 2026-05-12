# Random Forest Workflow for Gulf of Naples Chlorophyll - In situ and Projections

This repository contains the code supporting the manuscript:

Kokoszka, F., Asdar, S., Lefebvre, C., Buongiorno Nardelli, B., Mercogliano, P., Ribera d'Alcalá, M., Margiotta, F., and Iudicone, D.
“Chlorophyll Response to Freshwater and Wind Forcing in a Coastal Ecosystem: Recent Decades and Future Climate Scenarios”

Code repository prepared by Florian Kokoszka.
DOI: https://doi.org/10.5281/zenodo.20137722

Citation: Florian Kokoszka. (2026). fszk/GoN_RandomForest: CHLSAL v1.0 — Random Forest for Chlorophyll and Salinity (v1.0). Zenodo. https://doi.org/10.5281/zenodo.20137722

## Repository structure
### /code

Main notebooks used for the analyses and projections presented in the manuscript.

RandomForest_CHLSAL_GoN.ipynb
Main workflow for Random Forest training, validation, and future climate projections (RCP scenarios).
Extra_CHLSAL_GoN.ipynb
Complementary analyses including salinity parameterizations, Ekman layer calculations, sensitivity tests, and additional Random Forest experiments.
compiled_defs_RF_CHL_GON.ipynb
Collection of imported packages, utility functions, plotting routines, and shared definitions used across notebooks.

### /data

Example dataframes that can be directly used within the notebooks.

Included datasets contain processed variables used for the Random Forest analyses and climate projections.
These files are provided as to reproduce the workflow and figures presented in the manuscript.

## Notes

The repository is intended to support transparency and reproducibility of the analyses presented in the manuscript.
Some external datasets referenced in the study may require access through their original repositories or providers.

## Citation

If using this repository or parts of the workflow, please cite the associated manuscript and repository DOI once available through Zenodo.

Florian Kokoszka. (2026). fszk/GoN_RandomForest: CHLSAL v1.0 — Random Forest for Chlorophyll and Salinity (v1.0). Zenodo. https://doi.org/10.5281/zenodo.20137722

# Modelled Benthic Carbon Flux Analysis at L4 Station
- Title: Benthic Carbon Flux Visualisation for 1D GOTM-ERSEM simulations of the Western Channel Observatory L4 Station
- Keywords: marine ecology, carbon flux, benthic ecosystem, model visualisation
- Description: Jupyter notebook analyzing and visualising carbon fluxes in detailed and simplified ERSEM benthic ecosystem models
- Related publication: Siedlecki et al (2025). Sediment Biogeochemistry Model Intercomparison Project (SedBGC_MIP): motivation and guidance for its experimental desig. Submitted to Geoscientific Model Development.
- License: Creative Commons Attribution 4.0 International (CC BY 4.0)

## Visualisation of Modelled Benthic Fluxes for WCO L4 Station
This notebook processes and visualises carbon fluxes in 1D GOTM-ERSEM setup, comparing the results of detailed and simplified benthic ecosystem models applied to the Western Channel Observatory L4 Station (50°15.00'N, 4°13.02'W). It generates graph visualisations showing the flow relationships between different ecosystem components. More about the Western Channel Observatory: https://www.westernchannelobservatory.org.uk/. ERSEM code is available at https://github.com/pmlmodelling/ersem.

Author: Gennadi Lessin, Plymouth Marine Laboratory 
Date: April 2025

## Requirements
- graphviz
- xarray
- pandas
- numpy
- matplotlib

## Data Sources
L4_ERSEM_full_benthos_2016.nc - outputs of 1D simulation with full ERSEM benthic model
L4_ERSEM_benthic_return_2016.nc - outputs of 1D simulation with simple ERSEM benthic model

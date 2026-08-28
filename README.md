# Deep decarbonization model

Calliope model and data for exploring climate impacts, land-use constraints, and near-optimal adaptation pathways in Brazil’s energy system.

# Climate change impacts on Brazil’s energy transition

This repository contains the Calliope model, scenario configurations, and analysis scripts developed to investigate how climate change may affect Brazil’s decarbonized energy system and how the system can adapt through technological and spatial flexibility.

The analysis combines climate-induced changes in renewable-energy resources with land-use restrictions in a spatially explicit, sector-coupled energy system model. Near-optimal solutions are explored using SPORES to identify alternative infrastructure configurations within 10% of the least-cost solution.

## Scenarios

The study comprises six core scenarios, combining two land-use regimes and three climate conditions.

### Land-use regimes

- **Technical potential (`baseline`)**: protected areas, public forests, Indigenous territories, Quilombola territories, rivers and areas with slopes greater than 10% are excluded from infrastructure expansion.
- **Conservation (`conservation`)**: applies all technical-potential exclusions and additionally excludes priority areas for biodiversity conservation.

### Climate conditions

- **No climate change (`noclimate`)**: reference renewable resource availability.
- **SSP2–4.5 (`ssp245`)**: intermediate climate change pathway.
- **SSP5–8.5 (`ssp585`)**: high-emissions climate change pathway.

Climate-related changes are applied to hydropower, onshore wind and solar resources. Hydropower projections are based on an ensemble of ten climate models and three hydrological models, while wind and solar changes are derived from CMIP6 climate-change factors.

The scenario names follow this convention:

```text
scenario_[CLIMATE]_[LAND_REGIME]_[YEAR]




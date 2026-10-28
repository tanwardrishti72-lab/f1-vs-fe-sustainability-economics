# F1 vs Formula E: Freight Emissions and Abatement Costs

I wanted to compare how F1 and Formula E move their freight, and what it would cost to cut the emissions from it.

## What I found
- Traditional long-haul freight between races produces about 3,627 tCO2e across the three circuits I looked at ([names]).
- Switching to pre-staged sea freight and regional road freight cuts emissions on those legs by over 97%.
- Cost per tonne of CO2e saved:
  - Regional calendar clustering: $9.19, the cheapest option
  - HVO biofuel trucks: $13.44
  - Sustainable aviation fuel: $180.00, by far the most expensive

## How I did it
- Followed GHG Protocol Scope 3, Category 4 (upstream transport and distribution).
- Used DEFRA emission factors: air freight 602 g CO2e/t-km, sea freight 16, biofuel trucking 19.
- Abatement cost ($/tCO2e) = extra cost ($) ÷ CO2e reduced (tCO2e)

## Files
- `motorsport_emissions_mac_model.csv`: the data and calculations
- `README.md`: this write-up

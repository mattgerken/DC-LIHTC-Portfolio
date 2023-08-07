# Analysis of DC's LIHTC Portfolio
This project is an analysis of DC's [Low Income Housing Tax Credit (LIHTC)](https://www.huduser.gov/portal/datasets/lihtc.html) portfolio. The knitted results are publicly available [here](https://mattgerken.github.io/DC-LIHTC-Portfolio/) and are organized into the following five sections:

1. **Replicating Chicago's racial equity impact assessment**: The City of Chicago conducted a racial equity impact assessment (REIA) of its LIHTC portfolio. I replicated several of its figures and tables for DC's context, mapping LIHTC developments against the share of neighborhood (census tract) residents of different racial/ethnic identities.

2. **Supplementary analysis of DC's LIHTC portfolio**: I include a timeline (1988-2019) of when LIHTC units in the District were placed into service with a breakout by Ward. I also consider the location of LIHTC developments relative to the prioritization they were given by Urban Institute's Emergency Rental Assistance Priority (ERAP) Index.

3. **Co-location of LIHTC with neighborhood amenities**: I show the number of neighborhood amenities by DC planning area and Ward, for neighborhoods with and without LIHTC, and the number of amenities within a quarter mile (~5-minute walk) and half mile (~10-minute walk) of LIHTC developments.

4. **Urban Institute Spatial Equity Data Tool**: I uploaded the DC LIHTC portfolio data to Urban Institute's Spatial Equity Data Tool to determine the demographic and spatial distribution of LIHTC units relative to the broader District.

5. **Follow-up analysis**: After presenting the first four sections at an initial meeting, project stakeholders asked for a few additional analyses. These include housing type (new construction, acquisition and rehab, or both), data on the Tenant Opportunity to Purchase Act (TOPA), school quality, Affirmatively Furthering Fair Housing (AFFH) data, and value of land.

# Data and Tools

This analysis relies exclusively on the following publicly-available data sources and tools.

Data

* HUD's [LIHTC database](https://lihtc.huduser.gov/)
  
* 2021 American Community Survey (ACS) 5-year estimates (read in via the tidycensus package)
  
* Locations of neighborhood amenities (available through Open Data DC), including aging services facilities, recreation facilities, primary care centers, libraries, charter schools, public schools, DC Street Car, grocery stores, and Metro station entrances

* Urban Institute's [Emergency Rental Assistance Priority (ERAP) Index](https://www.urban.org/data-tools/where-prioritize-emergency-rental-assistance-keep-renters-their-homes)

* Urban Institute's [Education Data Explorer](https://educationdata.urban.org/data-explorer)

* OSSE's 2021 [DC School Report Card](https://osse.dc.gov/page/dc-school-report-card-resource-library)

* HUD's July 2020 [Affirmatively Furthering Fair Housing](https://datacatalog.urban.org/dataset/data-and-tools-fair-housing-planning) data   

* Open Data DC [Integrated Tax System Public Extract](https://opendata.dc.gov/datasets/integrated-tax-system-public-extract/explore)

* Tenant Opportunity to Purchase Act (TOPA) data available via [Housing Insights](http://housinginsights.org/)

Tools

* Urban Institute's [Spatial Equity Data Tool](https://apps.urban.org/features/equity-data-tool/)

# Results

The knitted results are publicly available [here](https://mattgerken.github.io/DC-LIHTC-Portfolio/).

![moi](https://github.com/mattgerken/DC-LIHTC-Portfolio/assets/69599248/e2f7cab0-9a7f-474f-a2f6-01a92813192b)


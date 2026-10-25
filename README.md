# Exploring Patterns of Environmental Justice: Historical HOLC Redlining and Los Angeles County

## Purpose
This repository contains an analysis of historical redlining in Los Angeles, CA, for EDS 223: Geospatial Analysis & Remote Sensing. Redlining was a discriminatory practice in which neighborhoods were graded based on their perceived risk for mortgage lending, often disadvantaging communities based on race and income. This project examines the relationship between historical Home Owners’ Loan Corporation (HOLC) grades and present-day neighborhood conditions using EPA EJScreen data on low-income households, life expectancy, and environmental conditions. It also uses bicycle and pedestrian crash data from 2020–2025 to explore whether historical redlining is associated with differences in crash reports and fatalities across neighborhoods.

## Repository Overview
- `HW2.qmd`: Quarto document containing all code, maps, figures, tables, and written interpretation.
- `HW2.pdf`: Rendered version of the Quarto document.
- `data/`: All data used in the analysis. This folder is listed in .gitignore.
  
```{r}
EDS223-HW2
│   README.md
│   HW2.pdf
│   HW2.qmd
├── .quarto
     └───typst
└───data
     └───ejscreen
     └───SWITRS_LA
     └───mapping-inequality
```

## Data Access

### EJ Screen
The data comes from the U.S. Environmental Protection Agency's EJScreen: Environmental Justice Screening and Mapping Tool. EJScreen has since been taken down from the EPA website, but the data is still accessible by the public using this [unofficial archived version](https://pedp-ejscreen.azurewebsites.net/).

The dataset used for this analysis was provided by Annie Adams as a [downloadable folder](https://eds-223-geospatial.github.io/assignments/HW1.html) through Environmental Data Science 223 (EDS 223) at the University of California, Santa Barbara (UCSB).

### HOLC Redlining
Researchers at the University of Richmond digitized maps and information from the Home Owners’ Loan Corporation (HOLC) as part of the [Mapping Inequality project](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58). These maps show how neighborhoods were graded based on perceived lending risk. This analysis uses HOLC grade designations for Los Angeles, California.

Additional information about the original maps and data is available [here](https://dsl.richmond.edu/panorama/redlining/data).

### Bike and Pedestrian Crash Reports
The bicycle and pedestrian crash data comes from the Statewide Integrated Traffic Records System (SWITRS), which collects and processes information about traffic collisions. The data is available through the [Transportation Injury Mapping System (TIMS)](https://tims.berkeley.edu/), developed by UC Berkeley SafeTREC. This analysis uses crash reports from 2020 through 2025. The metadata is available in the [SWITRS Codebook](https://tims.berkeley.edu/help/crashdata/switrs-codebook.php).

## Author
Sarah A. Hinkley: [GitHub Profile](https://github.com/sarahhinkley)

## References
- U.S. Environmental Protection Agency. (2023). EJScreen: Environmental Justice Screening and Mapping Tool (Version 2.2). Archived version: https://pedp-ejscreen.azurewebsites.net/
- Robert K. Nelson, LaDale Winling, Richard Marciano, Nathan Connolly, et al. (2026). *Mapping Inequality, Redlining in New Deal America*, accessed October 15, 2026. https://dsl.richmond.edu/panorama/redlining/.
- Transportation Injury Mapping System (TIMS). (2026). *Safe Transportation Research and Education Center*, University of California, Berkeley, accessed October 15, 2026. https://tims.berkeley.edu/about.php.

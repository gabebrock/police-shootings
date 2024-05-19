# A Case Study on the Relationship between Police Residence and Fatal Police Shootings

This document provides an overview of the project structure and usage for the case study on the relationship between police residence and fatal police shootings, exploring the correlation and impact of officers residing in the cities they serve on fatal police shootings.

## Abstract

This study investigates the relationship between police residence and fatal police shootings using a data science approach. It aims to discern patterns, trends, and potential biases associated with geographical proximity of police officers to the communities they police from 2015 to 2023.

## Setup

To run the analyses, you will need to install the following R packages:

```r
library(tidyverse)
library(usmap)
library(sf)
library(infer)
library(moderndive)
```

## Hypotheses

1. There is no difference in the mean number of fatal shootings per agency based on whether a majority of officers live in the city they serve versus cities where they do not.
2. There is no relationship between the percentage of the police force that resides in the city they serve and the number of fatal shootings.

## Methods

### Data Tidying and Wrangling

Data from various sources like `.csv` files are loaded and processed to create a tidy dataset suitable for analysis.

#### Counting Shootings

Fatal shootings are counted by agency, focusing on the top 25 agencies with the most incidents.

#### Mapping Shootings

Locations of police-involved shootings from 2015 to 2023 are mapped using geographical visualization libraries.

### Statistical Analysis

Hypotheses are tested using linear regression models to evaluate the relationship between officer residency percentages and fatal shootings.

## Results

Results are presented through multiple linear regression analysis, hypothesis testing, and visualizations such as bar plots and maps.

## Conclusion

The study concludes with insights into the potential impact of police residence on fatal shootings and provides evidence-based recommendations for policy-making and police training.

## Running the Analysis

To reproduce the results, execute the code chunks embedded within the R Markdown document. Each section corresponds to different stages of the analysis, from data preparation to final hypothesis testing and visualization.

### Output Configuration

Output is configured to be rendered as an HTML document with options for code folding and displaying code summaries.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
```

This Markdown file provides a structured and detailed guide for understanding and navigating the case study on the relationship between police residence and fatal police shootings.

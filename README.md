# NatHazard-US
Multivariate Statistical Assessment of Natural Hazard Risk in the United States


This repository contains R scripts for analyzing county and state-level risk data using various multivariate statistical techniques. The analysis includes data cleaning, exploratory data analysis, and clustering. 

## Source
Data is sourced from FEMA Natural Hazard Risk data. It includes data about the expected annual losses to individual natural hazards, social vulnerability and community resilience, available at county and Census tract levels.
https://www.fema.gov/flood-maps/products-tools/national-risk-index

## Analysis

- Analysis of county-level risk data.
- Analysis of state-level risk data.

## Requirements

- R programming language
- Required R packages:
  - `dplyr`
  - `ggplot2`
  - `cluster`
  - `MVN`
  - `mvnormtest`
    
### Steps

1. **Load and inspect data**

2. **Sample and clean data**

3. **Statistical analysis**
   - Pairs plot and correlation matrix
   - Variance-covariance matrix
   - Euclidean and Mahalanobis distances

4. **Normality testing**

5. **Clustering**
   - Hierarchical clustering
   - K-means clustering

## Additional Analysis

- Hierarchical clustering results are saved to text files for further analysis (e.g., in Tableau).

## Authors

Shagun Sengupta  
EAS 635 Multivariate Statistics






This Project serves as a standalone project created for EAS 635- Multivariate Statistics for
Environmental Science at the University of Michigan School for Environment and Sustainability.

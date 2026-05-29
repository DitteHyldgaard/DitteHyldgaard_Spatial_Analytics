# Spatial Analytics Final Project

## Spatial Relations Between DF Voters and Non-Western Immigrant Populations
Author: Ditte Hyldgaard Danielsen 

This repository contains my final project for the Spatial Analytics course 2026, which investigates the spatial relationship between support for Dansk Folkeparti (DF) and the distribution of non-western immigrant populations across Danish municipalities. 

## Contents

* `Final_Project_Script.Rmd` — main R Markdown analysis script
* `Final_Project_Script.html` — rendered HTML version of the analysis for easy access to 
* `data/` — datasets used in the project
* `output/` — exported maps, figures, and interactive visualizations

## Methods Used

* Choropleth mapping
* Pearson correlation analysis
* Bivariate mapping
* Local Moran’s I (LISA) spatial autocorrelation

## Software Used 

The project was developed in:

* R 4.5.1
* RStudio 2025.05.1+513

Required R packages:

* sf
* tmap
* tidyverse
* leaflet
* spdep
* htmlwidgets

## Reproducing the analysis 

To reproduce the analysis: 

1. Download the project folder and unzip
2. Open `Final_Project_Script.Rmd` in RStudio 
3. Ensure required packages are installed (Can be done easily by un-quoting the install.packages chunk)
4. Knit the document to HTML

Processed datasets are already included in the repository.


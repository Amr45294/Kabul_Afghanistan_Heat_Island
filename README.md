
# Kabul_Afghanistan_lab3 README

## Lab Overview

This document provides guidelines and information for Lab 3, titled "Kabul_Afghanistan_lab3", focusing on geospatial data analysis of temperature variations and urban land cover in Afghanistan, with a specific focus on Kabul. This lab is part of a series designed to explore environmental and urban planning issues using geospatial data.

## Author Information

- **Author:** Jordan Ayala
- **Contributor:** Ali Mounim Rajabi
- **Date:** 2024-04-17

## Objective

The main objective of this lab is to:
- Analyze temperature data across Afghanistan and specifically in Kabul.
- Explore the land cover of Afghanistan using satellite imagery.
- Examine the phenomenon of urban heat islands in Kabul.

## Requirements

### Software

- R (version specified by your installation)

### Libraries

Before starting the lab, ensure you have the following R packages installed and loaded:
- `terra`
- `geodata`
- `rnaturalearth`
- `ggplot2`
- `tidyterra`
- `devtools`
- `sf`
- `tidyverse`

You can install any missing packages using the R command `install.packages()`.

### Data

Data files required for this lab include:
- Land cover TIFF files for Afghanistan.
- Administrative boundary data for Afghanistan and city-specific data for Kabul.

### Installation

Ensure that you have installed the required packages using the following commands in your R environment:

```r
install.packages(c("terra", "geodata", "rnaturalearth", "ggplot2", "tidyterra", "devtools", "sf", "tidyverse"))
```

## Instructions

### Step 1: Setup Environment

Load the necessary libraries to ensure all functions and data manipulations can be performed:

```r
library(terra)
library(geodata)
library(rnaturalearth)
library(ggplot2)
library(tidyterra)
library(devtools)
library(sf)
library(tidyverse)
```

### Step 2: Data Loading

1. Load the land cover data and the administrative boundaries for Afghanistan.
2. Identify and load the urban area boundary and city dataset for Kabul.

### Step 3: Analysis

Follow the steps outlined in the provided R script to:
- Map average temperatures across Afghanistan and within Kabul.
- Analyze the land cover within the urban extents of Kabul.
- Investigate and visualize urban heat islands in Kabul.

## Resources

For additional guidance and reference material, consult the following resources:
- Geodata from UC Davis: [UC Davis Geodata Repository](https://geodata.ucdavis.edu/geodata/)
- OpenStreetMap Data Extraction: [OSMData Tutorial](https://rpubs.com/timothyfraser/osmdata)
- Global land cover dataL: [https://drive.google.com/file/d/1gNi5QPe78T_B355gVNyIWrNhK4bgmT2W/view?usp=drive_link]
- Asia land cover data: [https://drive.google.com/file/d/1XSqeLxcOlZ-yiDteBlve1aLC07pqfVho/view?usp=drive_link]

## Output

The final output will be a series of maps and visualizations in HTML format, displaying the analysis of temperature data, land cover, and urban heat islands.

---

This README document provides all essential details for running and understanding the lab. Adjustments can be made to include any specific details about the environment setup or additional steps.

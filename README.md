
## Title: Determining best suited EEZ's on the West Coast US for developing marine aquaculture
#### 🤠 Author: Flora Hamilton | floraham@github.io 
#### 📦 Repo Link: https://github.com/floraham/xxxx
This Github repository contains a .Rmd notebook. We use 3 datasets to conduct this analysis as described below. 

## Overview
Marine aquaculture has the potential to play an important role in the global food supply as a more sustainable protein option than land-based meat production. Gentry et al. mapped the potential for marine aquaculture globally based on multiple constraints, including ship traffic, dissolved oxygen, bottom depth.

## Objectives 
The goal of this project is to determine which Exclusive Economic Zones (EEZ) on the West Coast of the US are best suited to developing marine aquaculture, and we use several species of oysters for a demonstration. 

## Outputs
- an analysis of suitable EEZ's on the West Coast for several species of oysters, including visualizations. 
- a generalizable workflow for other species of interest in aquaculture

## Spatial Skills 
- combining vector/raster data
- resampling raster data
- masking raster data
- map algebra

#### 🔎 Dataset descriptions:

#### Data
- 🌡️ Sea Surface Temperature
  - We will use average annual sea surface temperature (SST) from the years 2008 to 2012 to characterize the average sea surface temperature within the region. The data we are working with was originally generated from NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1.
- 🌊 Bathymetry
  - To characterize the depth of the ocean we will use the General Bathymetric Chart of the Oceans (GEBCO).

- 🚩Exclusive Economic Zones
  - We will be designating maritime boundaries using Exclusive Economic Zones off of the west coast of US from Marineregions.org.


### Repository Structure 
```
aquaculture-eez
 │   README.md  
 │   aquaculture-eez.ipynb  
 │   .gitignore 
 └───data
      └─── |  average annual sst's 
           |  depth.tif
           |  wc region files 
         
           
```
Data Download Instructions:
The data associated with this assignment is too large to include in the GitHub repo. Data should be stored locally and added to .gitignore file. Download data from [here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view?usp=sharing).


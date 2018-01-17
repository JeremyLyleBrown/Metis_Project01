# MTA Project
#### by Brian K, Chris G, Jeremy B, and Laura C

Our goal was to recommend times and locations to place WomenTechWomenYes’s street teams.  Street teams will be placed at MTA subway stations to maximize attendance and contributions to WTWY summer gala.

We analyzed traffic volume and local income data.  We also examined proximity to large, local technology companies to balance maximizing attendance versus maximizing contributions. By incorporating IRS income data by ZIP code, our goal will be to identify a set of subway stations and days of the week for WTWY to optimize the placement of their street teams for collecting signatures.

## Project Setup

#### Installations

Install basemap - instructions here: https://matplotlib.org/basemap/users/installing.html

If you're missing some of the libraries in the scripts, you may need to use _pip install_ or a similar method. 

#### Data Sources
Download IRS income tax statistics data here: [https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2015-zip-code-data-soi](https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2015-zip-code-data-soi)

It is the first .csv file, the link says '2015' followed by '(all States, includes AGI).'

Keep this file in the main directory.



Download subway map data here:
[https://data.cityofnewyork.us/Transportation/Site_Subway/6td2-7qwm](https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2015-zip-code-data-soi)

Click the blue "Export" button, and scroll down to download as CSV.

Keep this file in the main directory.

## Guide

To replicate our project, run these scripts in the following order via Jupyter Notebook:

- [1\_MTA\_turnstile\_analysis.ipynb](https://github.com/JeremyLyleBrown/Metis_Project01/blob/master/1_MTA_turnstile_analysis.ipynb)
- [2\_income\_by\_zip.ipynb](https://github.com/JeremyLyleBrown/Metis_Project01/blob/master/2_income_by_zip.ipynb)
- [3\_Map\_Plot.ipynb](https://github.com/JeremyLyleBrown/Metis_Project01/blob/master/3_Map_Plot.ipynb)

Please see our presentation [here](https://github.com/JeremyLyleBrown/Metis_Project01/blob/master/Challenge_1_MTA_Project.pdf).

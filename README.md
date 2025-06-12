# Wildfire Data Reporting: Errors Caused by Wildfire Complexing

## Project Description:
Recent summers have seen increasingly large and damaging wildfires. Fueled by climate change, wildfires are burning more structures, requiring more resources, and becoming more complicated to contain. As these trends take hold, more wildfires are being managed as "complexes" - a management construct that creates a 'container' for small member fires. When fires are added to a complex, moved between complexes, or removed from complexes, this can create errors in the data that is reported. The errors can cause under- or over-estimates of acres burned, resources used, and other parameters. Our research uses data from ICS 209 situation reports to study wildfire complexing. As we search for the data errors, we hope to understand how and why they occur. Better data will allow better accountability, and better understanding of wildfire in every arena, from the impacts of climate change, to the appropriate allocation of resource expenses.

## Data:
The four datasets used in these notebooks were given to us by our partner, Lise Ann st. Denis from the CO-WY Resilience Engine. The datasets, i_fod, c_summary, c_daily, and i_ref, contain information derived from the ICS 209 plus dataset, which is a refined "science grade" version of the ICS 209 situation report forms filled out on incidents. So far, our study has focused on exploratory data analysis, and observing trends over time in a variety of parameters.

* i_fod: contains ID numbers, which connect individual fires to the FOD (Fire Occurrence Database)
* c_summary: this dataset is a "nexus" for the other datasets, and provides important summary data.
* c_daily: time-series data which tracks developments over the course of the incident.
* i_ref: reference data, for example geospatial data.

<NOTE: the i_fod and c_summarry notebooks seem to be unavailable. Could this be due to an issue with the data being unavailable?>

## Instructions for running the workflow
The notebook was imported into GitHub from colab. In colab, the notebook runs properly however in order for it to run properly in github, the file paths may need to be edited so that the data can be properly loaded into the notebooks from the .csv files (these are uploaded in the repository).

Some plots in the notebooks have an issue with lines 9 and 13 in their code, and may need to be run twice (the first of these is in the i_fod notebook). If a particular plot doesn't run properly, try un-commenting lines 9 and 13, running the cell, then commenting out those lines and running it again.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15331349.svg)](https://doi.org/10.5281/zenodo.15331349)

# CMPINF 0010 Final Project
**Team Nucleus**

## Team Members
* Liam Woodward, low21@pitt.edu
* Mathew Kennedy, mrk98@pitt.edu
* James Rabuzzi, jar310@pitt.edu

## Datasets
We used [Covid-19 data from Allegheny County](https://data.wprdc.org/dataset/allegheny-county-covid-19-tests-cases-and-deaths/resource/0f214885-ff3e-44e1-9963-e9e9062a04d1) that describes the Covid-19 cases, deaths, and individuals tested to the present date.

We also used [Public Art data from the City of Pittsburgh](https://data.wprdc.org/dataset/city-of-pittsburgh-public-art/resource/00d74e83-8a23-486e-841b-286e1332a151) that describes the different pieces of public art that can be found in the city, along with helpful information about each one.

**THIRD DATASET**

## Abstract
We were tasked with identifying the "best neighborhood" in the City of Pittsburgh. To accomplish this, we leveraged Covid-19 data and Public Art data as metrics with which to grade neighborhoods.We decided to use Covid-19 data because the Covid-19 pandemic is one of the most prominent issues currently, and any neighborhood that purports to be the best must be handling Covid-19 well. Public art was chosen as a metric because it would be unique and was a way to measure culture in neighborhoods. We combined these different metrics by assigning weights to each one and calculating a score for each neighborhood.

`Covid-19.ipynb` is the notebook analyzing Covid-19 data in various Pittsburgh neighborhoods.
`Public Art.ipynb` is the notebook analyzing Public Art in various Pittsburgh neighborhoods.

`Final Report.ipynb` is the notebook combining these metrics to identify the "best neighborhood" in Pittsburgh.

The neighborhood we identified as the best is Allegheny Center. Allegheny Center placed 2nd in our public art metric, and 58th in our Covid-19 metric, but was only 3% worse than the best neighborhood in the Covid-19 data. We identified Allegheny County as the best by analyzing the top 5 public art neighborhoods and choosing the one with the best Covid-19 score. Allegheny Center was a close 2nd in the Public Art data, and had a significantly better Covid-19 score than the other four neighborhoods.

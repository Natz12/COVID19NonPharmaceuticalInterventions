# CAN-NPI: A Curated Open Dataset of Canadian Non-Pharmaceutical Interventions in Response to the Global COVID-19 Pandemic

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Non-pharmaceutical interventions (NPIs) have been the primary tool used by governments and organizations to mitigate the spread of the ongoing pandemic of COVID-19. Natural experiments are currently being conducted on the impact of these interventions, but most of these occur at the subnational level - data not available in early global datasets. We describe the rapid development of the first comprehensive, labelled dataset of NPIs implemented at federal, provincial/territorial and municipal  levels in Canada to guide COVID-19 research. For each intervention, we provide: a) information on timing to aid in longitudinal evaluation, b) location to allow for robust spatial analyses, and c) classification based on intervention type and target population, including classification aligned with a previously developed measure of government response stringency. 

This initial dataset release spans January 1st, and March 31st, 2020; bi-weekly data updates to continue for the duration of the pandemic. This novel dataset enables robust, inter-jurisdictional comparisons of pandemic response, can serve as a model for other jurisdictions and can be linked with other information about case counts, transmission dynamics, health care utilization, mobility data and economic indicators to derive important insights regarding NPI impact. 

Here we show the count of recorded interventions by time in the dataset:

![Dataset Intervention Count](doc/img/intervention-count.png)

## Get the Data

You can use this direct link to get the data, which is stored in CSV format in this repository.

| Name  | Content | Rows | Size |  Link |
| --- | --- | --- | --- | --- |
| `npi_canada.csv` | All Canadian NPIs | 1640 | 5.46 MB | [Download](https://raw.githubusercontent.com/jajsmith/COVID19NonPharmaceuticalInterventions/master/npi_canada.csv) |

Alternatively you can clone this GitHub repository, where the dataset is named `npi_canada.csv`. The repository also contains notebooks for visualizations and demonstrations with the data.

```
git clone git@github.com:jajsmith/COVID19NonPharmaceuticalInterventions.git
```


## Access and Details

The codebook and additional details can be found at https://docs.google.com/spreadsheets/d/16jZ8tdPS9x8kRHAi5CRh8iKfDshg0AMbfFLJ9ysgV9U/edit?usp=sharing

**Time Period:** January 1, 2020 to March 31, 2020.


## Methods

Our documentation on the protocol followed to compile this dataset is being completed and will be shared shortly.

## Interested in Contributing?

If you have a correction or addition, please open a github issue.

Join the team or contact us at [howsmyflattening.ca](https://howsmyflattening.ca/#/home)


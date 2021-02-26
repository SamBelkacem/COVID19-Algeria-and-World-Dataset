# COVID19-Algeria-and-World-Dataset
A coronavirus dataset with 104 countries constructed from different reliable sources, where each row represents a country, and the columns represent geographic, climate, healthcare, economic, and demographic factors that may contribute to accelerate/slow the spread of the COVID-19. The assumptions for the different factors are as follows: 

- **Geography:** some continents/areas may be more affected by the disease
- **Climate:** cold temperatures may promote the spread of the virus
- **Healthcare:** lack of hospital beds/doctors may lead to more human losses
- **Economy:** weak economies (GDP) have fewer means to fight the disease
- **Demography:** older populations may be at higher risk of the disease

The last column represents the number of daily tests performed and the total number of cases and deaths reported each day.

## Data description
<img src="./Images/Data description.png">

## Countries in the dataset by geographic coordinates
<p align="center"> <img src="./Images/Countries by geographic coordinates.png"> </p>

- **Europe:**           33 countries
- **Asia:**             28 countries
- **Africa:**           21 countries
- **North America:**    11 countries
- **South America:**     8 countries
- **Oceania:**           3 countries

## Statistical description of the data
<img src="./Images/Statistical description of the data.png">

## Data distribution
<img src="./Images/Data distribution.png">

## Download
The dataset is available in an encoded CSV form on [GitHub](https://github.com/SamBelkacem/COVID19-Algeria-and-World-Dataset/).

## Python code
The Python Jupyter Notebook to read and visualize the data is available on [nbviewer](https://nbviewer.jupyter.org/github/SamBelkacem/COVID19-Algeria-and-World-Dataset/blob/master/Python%20code.ipynb).

## Data update
The dataset is updated every month with the latest numbers of COVID-19 cases, deaths, and tests. The last update was on January 20, 2021.

## Data construction
The dataset is constructed from different reliable sources, where each row represents a country, and the columns represent geographic, climate, healthcare, economic, and demographic factors that may contribute to accelerate/slow the spread of the coronavirus. Note that we selected only the main factors for which we found data and that other factors can be used. All data were retrieved from the reliable [Our World in Data](https://ourworldindata.org/coronavirus) website, except for data on:

- Continents: www.kaggle.com/statchaitya/country-to-continent
- Geographic-coordinates: www.kaggle.com/eidanch/counties-geographic-coordinates
- Temperatures: www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data
- Share of the population over 65 years old: https://data.worldbank.org/indicator/SP.POP.65UP.TO.ZS

## Citation
If you want to use the dataset please cite the following arXiv paper, more details about the data construction are provided in it.

```
@article{belkacem_covid-19_2020,
	title = {COVID-19 data analysis and forecasting: Algeria and the world},
	shorttitle = {COVID-19 data analysis and forecasting},
	journal = {arXiv preprint arXiv:2007.09755},
	author = {Belkacem, Sami},
	year = {2020}
}
```

## Contact
If you have any question or suggestion, please contact me at this email address: s.belkacem@usthb.dz

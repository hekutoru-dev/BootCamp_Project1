# Data-Analysis-Pollutants-vs-RespiratoryDiseases
A deep data analysis using Python and its libraries to analyze the relation between pollutants and respiratory diseases in Mexico City in 2016

## Background

Air pollution has been a growing problem during the last years around the world, not only for Global Warming implications, 
but also for its consequences regarding public health. According to the World Health Organization (WHO), there has been a
reported increase in the number of deaths associated to respiratory problems or diseases related to the air pollution.

In several studies, the principal pollutants that have been identified as responsible of the respiratory diseases are carbon
monoxide (CO), nitrogen oxides (NOx), particulate matter (PM10), volatile organic compounds (VOC) and ozone (O3).

The aim of this study was to identify the correlation between the respiratory emergencies and two of these pollutants, O3
and PM10.

## Resources:
The data used for this analysis (the air pollution and the health emergencies, respiratory diseases) was obtained from the API
“Datos Abiertos” (https://datos.gob.mx/) and several databases. More details on main Jupyter Notebook.

The analysis was conducted by Python libraries and the use of other tools as Jupyter Notebook and Excel. 

## Analysis
The analysis of the pollutants in the air was made with the databases obtained from the sources of “Datos Abiertos”. The
data obtained correspond to the pollutant readings per minute since 2001. The measures of the of O3 and PM10 levels, were
extracted by city and later the data from Mexico City was separated by municipalities. Then the data was plotted to see
the behavior of these two pollutants through time. The municipalities with missing data were dismissed, for the
purpose of this analysis. Treatment of the data in order to plot it is also shown in full Notebook.

The emergencies data was obtained from 2010 to 2016, which was the most recent data available; and was separated by city
and later was depurated to keep only the respiratory diseases and finally organized by municipality. The data was treated as
the pollutants data, in order to clean the plots and define if there was any relation between the pollutants and the number of
RDEs.

Once RDEs and the pollutants data were clear, they were plotted through time, to see if there was a correlation between them. 

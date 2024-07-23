# 
<p align="center">
<h1 align="center">Project of the City of Bern, Switzerland</h1>
  <p align="center"> This project aims to delve into and understand the capital of Switzerland while exploring various aspects of Data Analysis.</p>
</p>
<p align="center">
  <img src="https://i.ibb.co/B6bHMh4/bern-stadt.jpg">
</p>

# Project Overview
The City of Bern, also known as Berne, is the de facto capital of Switzerland. As of 2022, it has a population of approximately 144 447 inhabitants. While Bern is not the largest city in Switzerland, it ranks fifth in terms of population, following Zürich, Geneva, Basel, and Lausanne. 
The goal of this project is to analyze historical data from 1941 to the present day for the city of Bern, Switzerland, and to forecast potential future changes in various elements.

# Data Sources
I accessed the [Open Government Data (OGD) portal](https://www.bern.ch/open-government-data-ogd/ogd-nach-themen), which provides public data on topics such as finances, statistics, geodata, and more. For this project, I focused on gathering the most comprehensive datasets available, spanning from 1941 to 2022. I identified five datasets of particular interest:
1. **arbeitslose_seit_1921**: Unemployment values.
2. **bevoelkerungsbestand_seit_1941**: Population values from 1941 onwards.
3. **bevoelkerungsbestand_und_haushalte_seit_1850**: Population and household data from 1850 onwards.
4. **natuerliche_bevoelkerungsbewegungen_seit_1890**: Data on marriages, divorces, births, and deaths from 1890 onwards.
5. **wanderungsbewegungen_seit_1900**: Migration data, including the number of arrivals and departures from 1900 onwards.
  
# Objectives

- **Historical Analysis**: Examine trends and patterns in the historical data for Bern, including unemployment, population dynamics, household changes, natural population movements, and migration.
- **Forecasting**: Utilize the historical data to predict future trends in these areas, providing insights into potential future developments in Bern.

# First Insights
## Overall Population
- Maximum: In 1965, the population peaked at 163,084 inhabitants.
- Minimum: In 1999, the population declined to 126,467 inhabitants.
1. Natives (Swiss Citizens):
- Maximum: In 1965, there were 163,084 Swiss citizens.
- Minimum: In 1999, the number decreased to 126,467 Swiss citizens.
2. Immigrants:
- In 1945, there were only 3,886 immigrants.
- By the last analyzed year (2022), the immigrant population had increased significantly to 35,436.

## Graphics
1. Population of City of Bern from 1941 to 2022, plus the immigrates and natives flows 
![](https://i.ibb.co/T488hyn/graphics.jpg) <br/>
It's interesting to observe that the population peaked around 1965, declined until 2000, and then began to increase again until 2022. This trend suggests that the population of Bern might continue to grow, potentially reaching the same level as in 1965.

2. Miggration Patters over time
![](https://raw.githubusercontent.com/gboaventura93/Project_Bern/main/graphics/migrations.png) <br/>
This graph shows the ratio between the number of people who leave and arrive in Bern. Interestingly, this ratio does not correlate with the overall population trends. Regardless of the population size, the graph indicates that more people have consistently left Bern than arrived. Additionally, the ratio between departures and arrivals appears to be proportional over time.

3. Birth and Deaths over time
![](https://raw.githubusercontent.com/gboaventura93/Project_Bern/main/graphics/birth_death.png) <br/>
It's interesting to see that we can divide this graph into three parts: <br/>
I. **1941-1972**: Births > Deaths. The peak was around 1950, with births over 2200 and deaths around 1500, showing a 32% increase. <br/>
II. **1972-2008**: Deaths > Births. The highest death rate was around 1992, with approximately 1775 deaths, while births were around 1250, showing a 30% decrease. <br/>
III. **2008-2022**: Births > Deaths. Births have been increasing while deaths have been decreasing, except around 2012, when they were equal. <br/>
These trends show a direct relationship between population changes and the birth-to-death ratio. The population decline after 1965 can likely be explained by the second phase, where deaths outnumbered births.

4. Heatmap City of Bern
![](https://raw.githubusercontent.com/gboaventura93/Project_Bern/main/graphics/heatmap.png) <br/>
This graph illustrates the correlation between the analyzed variables, where values close to one indicate a strong relationship, and values close to zero indicate a weak relationship. Notably, there is a high correlation between arrivals and departures (0.98), and between total population and arrivals (0.95). Conversely, some variables have a negative correlation, such as marriages and immigrants (-0.78) or unemployment and natives (-0.84). <br/>
These correlations are valuable not just for comparison, but also for developing projects and applying machine learning techniques to leverage these relationships effectively.


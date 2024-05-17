# COVID 19 Data Exploration

# Source:
https://ourworldindata.org/covid-deaths

This project focuses on analyzing data related to the COVID-19 pandemic using SQL queries. 
The dataset provides information about COVID-19 cases, deaths, population, and vaccinations across the continents. The objective is to gain insights into and answer questions about the pandemic.

Using Africa as case study.

Here is a summary of the queries and the insights they provide:

Mortality Rate: This query calculates and shows the percentage of deaths in relation to the total number of cases. It helps us understand how likely contracting the virus would be.

Percentage of Population Infected: This query determines the percentage of the population that has contracted COVID-19, by comparing the total number of cases to the population size. We can evaluate the spread of the virus in various regions.

Highest Infection Rate: This query identifies the countries with the highest infection rate in per its population. It calculates the percentage of the population that has been infected and highlights the location with the highest value.

Highest Death Rate: This query identifies the country with the highest death rate per population. It calculates the percentage of the population that has died due to COVID-19 and highlights the location with the highest mortality rate.

Country with the Highest Death Count: This query determines the country that has experienced the highest total number of deaths. It provides insights into the countries most impacted by the virus.

Continent with the Highest Death Count: This query identifies the continent with the highest total number of deaths. It helps us understand the overall impact of the pandemic on a larger scale.

Global Cases per Day: This query presents the daily global COVID-19 cases, including the total number of new cases and new deaths. It also calculates the death rate as a percentage of new cases, giving us an indication of the severity of the virus over time.

Rolling Count of People Vaccinated: This query calculates the cumulative count of vaccinated individuals on each day. It tracks the total number of people vaccinated and presents it alongside the population size. Additionally, it shows the percentage of the population that has received the vaccine.

Some of the techniques used in this project include joins, CTEs, temp tables, window functions, and aggregate functions to derive insights from the data. In addition to the SQL queries, this project involves creating views to store the results of our analyses. These views can be used for further exploration, data visualization, and reporting purposes.

By analyzing the COVID-19 data using SQL, our project aims to provide meaningful insights into the impact of the virus on different regions, assess the effectiveness of vaccination efforts, and understand the severity of the pandemic over time. The findings from this project can contribute to informed decision-making, resource allocation, and the development of effective public health strategies.
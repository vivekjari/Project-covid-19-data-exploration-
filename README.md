## Covid-19 Data Exploration and Visualization

Large amount of data was gathered during the Covid-19 pandemic. Here we have two datasets, one with the information regarding covid-death and another regarding covid-vaccinations. This vast datasets give us an opportunity to explore questions like:

-Likelihood of dying if you contact covid in your country.
-What percentage of population infected with Covid?
-Countries with Highest Infection Rate compared to Population
-Countries with Highest Death Count per Population
-Total Population vs Vaccinations
-Percentage of Population that has recieved at least one Covid Vaccine


## Data

- ***Covid Deaths Data :*** new cases, total cases, new deaths, total deaths, deaths per million, new hospital admission, etc.
- ***Covid Vaccinations Data:***  country, location, total vaccines, people vaccinated, total vaccinations per hundred, etc.


## Tasks

-To run SQL queries in order to get desired information from the dataset.
-To join two datasets for the purpose of analysis.
-To export the derived information in the form of tables and create visualization dashboard in Tableau

## Checkpoints

The checkpoints for the assignment are as follows:

1. Load the Dataset in MySQL.

2. Perform EDA to look for null values and misaligned data types.

3. create new column : total deaths/total cases*100 as ‘deathpercentage’ to know the likelihood of dying if you contact covid.

4. create new column : total cases/population*100 as ‘percentinfected’ to know the percentage of populaton infected.

5. Find the maximum number of total deaths and group it by location to find the countries with highest death count.

6. Add total cases and total deaths to find the global numbers.
7. Now join the two datasets on primary key ‘location’, and ‘date’. Now add the new people vaccinated to form an attribute named – ‘rollingpeoplevaccinated’ to show total people vaccinated.

8. Now divide rollingpeoplevaccinated with total population to get the percentage of people vaccinated.

9. Now create view to store data for further visualization.

Tableau Dashboard:
https://public.tableau.com/app/profile/vivek.jariwala/viz/CovidDataExploration_17063601027430/Dashboard1






Covid-19 Data Exploration with SQL

This project explores Covid-19 datasets using SQL to analyze and uncover insights such as infection rates, death percentages, vaccination trends, and global statistics. The analysis demonstrates practical SQL skills including joins, aggregate functions, CTEs, temp tables, views, and window functions.

📂 Dataset

The data used comes from the Our World in Data Covid-19 dataset. It is divided into two main tables:

CovidDeaths → Contains cases, deaths, population, and continent information.

CovidVaccinations → Contains vaccination records by country and date

🛠️ Skills & Concepts Used

Filtering and ordering data

Aggregate functions 

Joins between tables

Window functions 

Common Table Expressions (CTEs)

Temporary tables

Creating views for visualization

📊 Analysis Performed

Initial Exploration

Selected relevant fields like location, date, total cases, deaths, and population.

Total Cases vs Total Deaths

Calculated the death percentage to understand the likelihood of dying if infected (example shown for Oman).

Total Cases vs Population

Measured the percentage of the population infected.

Countries with Highest Infection Rates

Found countries with the largest infection counts and percentage of population infected.

Countries with Highest Death Count

Identified countries with the highest reported deaths.

Continents with Highest Death Count

Grouped by continent to see the hardest-hit regions.

Global Numbers

Summarized worldwide total cases, total deaths, and global death percentage.

Vaccination Analysis

Joined CovidDeaths and CovidVaccinations to calculate:

Rolling count of people vaccinated.

Percentage of population vaccinated (using CTEs, temp tables, and views).


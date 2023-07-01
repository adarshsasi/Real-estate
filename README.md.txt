# Mortgage Analysis Project

This repository contains the code and documentation for the Mortgage Analysis Project. The project aims to provide actionable insights into mortgage-backed securities, geographic business investment, and real estate analysis. The goal is to predict potential monthly mortgage expenses for each region in the USA based on monthly family income and rental of real estate. The project also involves creating a dashboard to visualize key metrics and trends related to mortgages, rental income, costs, and demographic factors.

## Dataset Description

The dataset used in this project contains various variables related to mortgages, household debt, income, demographics, and more. These variables include:

- Second Mortgage: Statistics on households with a second mortgage
- Home Equity: Statistics on households with a home equity loan
- Debt: Statistics on households with any type of debt
- Mortgage Costs: Statistics regarding mortgage payments, home equity loans, utilities, and property taxes
- Home Owner Costs: Sum of utilities and property taxes statistics
- Gross Rent: Contract rent plus the estimated average monthly cost of utility features
- High School Graduation: High school graduation statistics
- Population Demographics: Population demographics statistics
- Age Demographics: Age demographic statistics
- Household Income: Total income of people residing in the household
- Family Income: Total income of people related to the householder

## Project Tasks

The project tasks are divided into four weeks:

### Week 1 - Data Import and Preparation

- Import the dataset and identify the primary key.
- Evaluate the fill rate of variables and devise plans for missing value treatment, explaining the reason for each treatment.

### Week 1 - Exploratory Data Analysis (EDA)

- Perform debt analysis by exploring locations with the highest percentage of households with a second mortgage and percent ownership above 10%. Visualize the results using a geo-map.
- Calculate bad debt using the provided equation and create pie charts to show overall debt and bad debt.
- Create box and whisker plots to analyze the distribution of second mortgage, home equity, good debt, and bad debt for different cities.
- Create a collated income distribution chart for family income, household income, and remaining income.

### Week 2 - Exploratory Data Analysis (EDA)

- Perform EDA on population density and age, creating new fields using weighted averages.
- Visualize population density and median age using appropriate chart types.
- Create bins for population and analyze the married, separated, and divorced population for each population bracket.
- Analyze rent as a percentage of income at an overall level and for different states.
- Perform correlation analysis using a heatmap and describe the findings.

### Week 3 - Data Pre-processing

- Use factor analysis to identify latent variables such as high school graduation rates, median population age, second mortgage statistics, percent ownership, and bad debt expense.

### Week 4 - Data Modeling

- Build a linear regression model to predict the total monthly expenditure for home mortgages loans. Run the model at a national level and, if necessary, at a state level.

### Data Reporting and Dashboard

- Create a dashboard using Tableau to visualize key metrics and trends.
- Include charts, such as box plots of average rent by type of place, pie charts for overall debt and bad debt, a geo-map showing locations with a high percentage of households with a second mortgage, a correlation matrix heatmap, and a pie chart for population distribution across different types of places.

## Getting Started

To get started with the Mortgage Analysis Project, follow these steps:

1. Clone this repository to your local machine.
2. Import the dataset into your preferred data analysis tool.
3. Run the code and scripts provided to perform the data import, preparation, exploratory data analysis, data pre-processing, and modeling tasks.


```bash
https://github.com/adarshsasi/Real-estate

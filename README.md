# How Do Socio-Economic Factors Influence Global Life Expectancy?
## An Exploratory Data Analysis & Report

This repository contains an R-based statistical analysis examining the relationship between global life expectancy and key socio-economic factors, including health expenditure, education expenditure, and national income classification.

## Project Overview

Life expectancy is a widely used indicator of population health and overall development. This project analyzes whether and how socio-economic investments and income level are associated with differences in life expectancy across countries.

The analysis addresses the following research questions:

 * How Has Global Life Expectancy Evolved Over Time?
 * How Does Health Expenditure Influence Life Expectancy?
 * How Does Education Expenditure Influence Life Expectancy?
 * How Does Life Expectancy Differ By Income Group?

## Data

The dataset includes country-level indicators sourced from the World Bank and related global databases. Key variables include:

* **Life.Expectancy.World.Bank**: Average life expectancy at birth
* **Health.Expenditure..**: Health expenditure as a percentage of GDP
* **Education.Expenditure..**: Government education expenditure as a percentage of GDP
* **IncomeGroup**: World Bank income classification (Low, Lower Middle, Upper Middle, High)

The data are aggregated at the national level and include some missing values, which are handled through standard R data-cleaning procedures.

## Methods

The analysis uses the following statistical methods:

* **Descriptive statistics and visualizations** to summarize distributions and identify patterns
* **Simple linear regression** to assess relationships between life expectancy and health and education expenditures
* **One-way ANOVA** to test for differences in mean life expectancy across income groups

These methods were selected based on variable types and research objectives, focusing on identifying associations rather than causal relationships.

## How to Run the Analysis

1. Clone this repository
2. Open the `.Rmd` files in RStudio
3. Install required packages (listed at the top of the R Markdown file)
4. Knit the document to HTML or PDF

## Tools and Technologies

* R
* RStudio
* tidyverse
* ggplot2
* knitr


# Financial and Sentiment Analysis 
**Data Engineering and Visualization Project**

This project is a dynamic Shiny Dashboard built with R and flexdashboard that integrates financial health metrics with public sentiment analysis. It provides a multi-faceted view of 15 global companies across 5 sectors (Technology, Entertainment, Healthcare, Auto, and Farm Products) from 2014 to 2023.

## Tech aspects
Language: R<br>
Interface: Shiny, flexdashboard<br>
Data Visualization: Plotly (interactive charts), Leaflet (geospatial mapping), ggplot2<br>
Data Engineering & Processing: tidyverse (dplyr, tidyr), readr, scales<br>
External Integration: New York Times API (News headlines and Sentiment analysis)

## Data Pipeline & Features
1. Data Cleaning & Transformation (ETL)
- Processed raw financial data from Balance Sheets and Income Statements.
- Implemented data tidying techniques to handle time series data (2014-2023), ensuring consistency across disparate sectors.
- Mapped company headquarters to geospatial coordinates for real-time mapping.

2. Interactive Economical Analysis
- Financial Ratios: Calculation and visualization of Debt Ratio, Current Ratio, and Return on Assets (ROA).
- Dynamic Filtering: Users can vizualized and investigate data by sector and specific company, with reactivity handled by Shiny's server-side processing.

3. NLP & Sentiment Analysis (API Integration)
- Data Acquisition: Pipeline built to fetch headlines via the New York Times API.
- Sentiment Scoring: Performed sentiment analysis on news headlines to correlate public perception with financial performance.
- Text Mining: Implemented frequency analysis to extract the "Top 5 Words" associated with each company per year.

4. Geospatial Visualization
- Interactive Leaflet map displaying company HQs, with marker sizes proportional to revenue, providing a global perspective on market influence.

## Authors
Paloma Guth Kronbauer and Zumratmo Zarifkhonova

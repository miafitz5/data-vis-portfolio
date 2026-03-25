# Mia's Data Visualization Portfolio

This portfolio showcases a series of data visualizations and dashboards created in R using the `flexdashboard` package. The work demonstrates a variety of data sources, visualization techniques, and insights gained throughout the process.

## Overview
- **Format:** R Markdown (`.Rmd`) rendered as a Flexdashboard
- **Tools/Libraries:** flexdashboard, ggformula, ggplot2, plotly, ggridges, dplyr, lubridate, viridis, tidyr, mosaic, Lock5Data, Stat2Data, maps, usdata, ggrepel, janitor, readr
- **Focus:** Animated graphs, faceting, color usage, time series, maps, and dashboard value boxes

## Pages & Visualizations

### Page 1: Refined Graphs
- **Animated and faceted graphs** using datasets like HomesForSale, Hawks, and Film
- Explores the impact of color, faceting, and animation in storytelling
- Example: Boxplots of home prices by state, scatterplots of hawk wing length vs. weight, and movie ratings vs. running time

### Page 2: Graphs with Time
- **Time series visualizations** using weather data (Lincoln Weather, Weather)
- Techniques: Color gradients, faceting by month/city, and tile plots
- Example: Average temperature trends in Lincoln, NE, and weather pattern comparisons between Chicago and Beijing

### Page 3: Maps
- **Geospatial visualizations** using US states and Virginia county data
- Example: ACT scores mapped by state, Virginia college locations with labels and point sizes by net price

### Page 4: Dashboard & Value Boxes
- **Bar and scatter plots** using workplace injury data
- **Value boxes** highlight key statistics (e.g., most injury days in California, unique cases in South Carolina, lowest average days away in 2007)

## Key Insights & Learnings
- Animated and faceted graphs can reveal hidden patterns
- Not every graph needs color to be effective
- Geospatial and time-based visualizations provide deeper context
- Value boxes are useful for summarizing key findings

## How to Reproduce
1. Open `Mia's Portfolio.Rmd` in RStudio
2. Install required R packages (see above)
3. Render the dashboard using the Knit button or `rmarkdown::render()`

## Repository
This project is tracked in the [data-vis-portfolio](https://github.com/miafitz5/data-vis-portfolio.git) repository.

---
*Created by Mia Fitzgerald*

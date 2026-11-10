# What's in Your Bag? Survey Analysis

## Project Overview

This project was completed as part of my Sampling and Survey Methods course at the University of Georgia. The purpose was to explore the types of items people carry in their bags and identify patterns in survey responses. Using R, I organized and analyzed survey data to better understand the frequency of different item categories and the geographic distribution of respondents.

## Data Source

The data were collected through a survey asking participants about the items they carry in their bags, their preferences, and their everyday habits. The cleaned dataset contains 76 responses and 13 variables, including bag type, item categories, and geographic location.

## Methodology

I used descriptive statistics and data visualization techniques in R to analyze the survey responses. Open-ended responses about unique items were grouped into broader categories to make comparisons easier. I then calculated the frequency of each category and created a horizontal bar chart to display the results. I also used respondents' reported states to create a U.S. map showing the geographic distribution of survey participation.

## Tools & Libraries

- **RStudio:** Data cleaning, statistial analysis, visualization, and writing and running the analysis
- **R Markdown:** Combining code, results, and explanations
- **maps package:** Creating the geographic visualization

## Key Findings

The most common category of unique items was Medicine/Personal Care, with 23 responses. Entertainment was the second most common category with 15 responses, followed by Food with 12 responses. School Supplies and Clothing Items were among the less frequently reported categories.

The geographic visualization showed that most survey participants were from Georgia, with 66 of the 76 responses coming from that state. These results provide insight into the items reported by the surveyed participants and the composition of the sample.

## Limitations

One limitation of this project is that the sample was relatively small and heavily concentrated in Georgia, meaning the results may not represent the broader U.S. population. Additionally, grouping open-ended responses into categories required some judgment, which could influence the results. The analysis was primarily descriptive and does not establish causal relationships.

## Reproducibility

To reproduce this analysis:

1. Download the `Whats_in_Your_Bag_Portfolio.Rmd` and `WhatsinYourBag_Public.csv` files from this repository.
2. Open the R Markdown file in RStudio.
3. Make sure both files are saved in the same folder.
4. Install the `maps` package if it is not already installed using `install.packages("maps")`.
5. Run the code chunks or click **Knit** to generate the HTML report.
6. Review the resulting frequency tables, bar chart, and geographic visualization.

## Project Files

- `Whats_in_Your_Bag_Portfolio.Rmd` — R code, analysis, and visualizations
- `WhatsinYourBag_Public.csv` — Cleaned survey dataset with identifying information removed

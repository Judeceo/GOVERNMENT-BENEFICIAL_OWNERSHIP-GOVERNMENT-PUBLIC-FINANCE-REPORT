# GDB Government Ownership & Public Finance Analysis

## Table Of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Result Findings](#result-findings)
- [Recommendation](#recommendation)
- [Limitations](#limitations)
- [Reference](#reference)

  ### Project Overview 

  The summary statistics reveal the distribution of the two governance metrics across the dataset. The beneficial ownership scores have a mean around 55.5 with a standard deviation of approximately 28.7, indicating some variability among countries. The public finance data scores have a mean around 66.7 with a standard deviation of about 46.0, suggesting a wider spread in the data.

The category counts show the number of countries in each region and subregion, highlighting the geographical diversity of the dataset. For example, Africa and Latin America and the Caribbean are well-represented, with multiple subregions such as Western Africa, Middle Africa, and Caribbean.

The analysis of the regional and subregional average scores reveals notable disparities in governance metrics across different geographical areas.

The charts show that some regions, such as Africa and Latin America and the Caribbean, tend to have lower average scores in beneficial ownership and public finance data, indicating potential governance challenges. Conversely, regions like Europe or North America (if present) might display higher scores, reflecting stronger governance indicators.

The correlation analysis between the beneficial ownership scores and public finance data scores shows a correlation coefficient of approximately 0.12. This indicates a very weak positive relationship, suggesting that higher beneficial ownership scores are only slightly associated with better public finance data scores across the countries in the dataset.

This weak correlation implies that improvements in one governance aspect do not necessarily predict improvements in the other, highlighting the complexity and multifaceted nature of governance indicators.

<img width="357" height="323" alt="image" src="https://github.com/user-attachments/assets/b9a6566d-e9ef-4334-aed2-8687fec20223" />


### Data Source

GDB Data: The primary dataset used for this analysis is the "GDB_Data.xlsx" file containing detailed information about the overall score by the country.

### Tools

- Excel - Data Cleaning & Analysis [Download here](https://Microsoft.com)
- PowerBi - Creating reports


### Data Cleaning Preparation

1. Data Cleaning & Formatting.
2. Data Loading and Inspection.

### Exploratory Data Analysis

- Distribution of scores across regions and subregions.
- identify any notable patterns or outliers.

### Result Findings

The analysis of outliers reveals countries with exceptionally high or low scores in beneficial ownership and public finance data.

From the data:

Colombia stands out with a notably high beneficial ownership score of 85.0 and a public finance score of 79.25, indicating relatively strong governance indicators in these areas.

Angola shows a low beneficial ownership score of 27.2 but a high public finance score of 81.7, suggesting disparities between different governance aspects within the country.

These outliers highlight the diversity in governance performance across countries, with some excelling in certain areas while lagging in others.

### Recommendation

Based on the insights, my recommendation;
- From the visualization, it appears that there is no strong linear correlation between these two metrics, as the points are quite dispersed without a clear trend. Some countries with high beneficial ownership scores also have high public finance data scores, but there are notable outliers on both ends.

This suggests that improvements in beneficial ownership transparency do not necessarily coincide with better public finance data, indicating that these governance aspects may need to be addressed independently.

The analysis identified the countries with the highest and lowest scores in beneficial ownership transparency and public finance data.

The top countries in beneficial ownership include Colombia, Bahamas, and Morocco, with scores of 85.0, 80.0, and 80.0 respectively. These countries demonstrate relatively high levels of transparency in ownership structures.

Conversely, the countries with the lowest beneficial ownership scores are Angola, Liberia, and Namibia, with scores of 36.0, 36.0, and 40.5 respectively, indicating areas where transparency could be improved.

- For public finance data, the leading countries are Angola, Ghana, and Mozambique, all with scores of 100.0, showing excellent data availability or quality in this area.

The countries with the weakest public finance data are Botswana, Liberia, and Namibia, with scores of 9.25, 10.0, and 16.0, highlighting significant gaps in data.

This variation suggests targeted efforts could focus on countries with low scores to improve transparency and data quality.



### Limitations

1. I have to remove all zero values from the governance_ci_beneficial_ownership_by_country column because they would have affected the accuracy of my conclusion.


### Reference

1. [GDB](https://globaldatabarometer.org/2025/06/global-data-barometer-data-visualization-challenge-2025/)

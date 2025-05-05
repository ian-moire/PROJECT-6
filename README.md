# # National Immunization and Health Survey Dataset
**1. Tableau[Link](https://public.tableau.com/app/profile/ian.moire/viz/Book1_17460999542570/VACCIANTIONTRENDSACROSSSURVEYYEARS#1)**

**2. Presentation[Link](https://docs.google.com/presentation/d/1eon7pHcQ-aUofkpP8Nft0lICDcpFDRZLfFQRMyS56g8/edit?slide=id.g35f391192_00#slide=id.g35f391192_00)**

## Background
The dataset provides vital information from health surveys conducted across multiple countries and years. These surveys assess vaccination coverage and other indicators that influence public health. By analyzing this dataset, we aim to better understand global health trends and the factors affecting vaccination success rates.

## Objective
The primary objective of this analysis is to uncover key insights about vaccination coverage and related health indicators. We aim to identify trends, regional disparities, and factors that contribute to vaccination success rates. These findings will inform future decision-making and resource allocation in public health.

## Research Questions
1. How has the vaccination percentage changed across different survey years?
2. What trends do we observe in specific vaccines (BCG, DPT, Fully Vaccinated, etc.) over time?
3. How do vaccination rates vary by country?
4. What factors might contribute to higher or lower vaccination rates in certain regions?

## Data Description
The dataset used in this analysis is the "immunization_national_ken" dataset from ***Data.Humdata.org***. It contains 350 records with features such as'ISO3','DataId','Indicator','Value','Precision','DHS_CountryCode','CountryName','SurveyYear','SurveyId','IndicatorId','IndicatorOrder',
'IsTotal', 'IsPreferred','SurveyType', 'DenominatorWeighted',and 'DenominatorUnweighted'. Missing values, duplicates, and outliers were addressed as Feature engineering metrics like ratios, percentages, and log-transformed features were added in the dataset.

## Methodology
The analysis will involve the following :

1. **Data Cleaning:** Resolved missing values and duplicates, and removed outliers using statistical methods like IQR
2. **Exploratory Data Analysis (EDA):** Visualized distributions, correlations, and trends using histograms, boxplots, line charts, and   heatmaps.
3. **Feature Engineering:** Created new metrics, including ratios between weighted and unweighted denominators, vaccination percentages, and log-transformed features.

## Significance
This analysis is instrumental in improving public health initiatives. By understanding vaccination coverage trends and identifying factors contributing to disparities, stakeholders can better target interventions and allocate resources. The engineered features and insights derived from this dataset have the potential to shape policies and ensure more equitable health outcomes globally.
## Conclusion
The analysis of the dataset has provided valuable insights into vaccination coverage and health survey data. By handling missing values, outliers, and duplicates, and applying exploratory data analysis and feature engineering, we have prepared the dataset for deeper insights.

## Summary of Key Findings
1. **Trends in Vaccination Indicators:** Significant variability in weighted denominators (DenominatorWeighted) across survey years.
2. **Correlations:** Strong correlations observed between weighted and unweighted denominators.
3. **Feature Engineering:** New metrics such as Weighted_Unweighted_Ratio provided deeper insights into scaling effects. Log transformations normalized skewed data, aiding in clearer visualizations and analysis.

## Implications
The findings highlight regions and survey years requiring greater attention to allow resource allocation by policymakers so as to use these insights to better distribute vaccines and health resources across countries.

## Limitations
The dataset is limited in size (252 rows post-cleaning), which may impact the generalizability of insights. Some indicators lacked data, which could limit interpretation. Outlier handling were based on statistical assumptions.

## Future Work
Develop predictive models to identify high-risk regions. Conduct a deeper dive into specific countries or regions to uncover localized trends. Combine this dataset with other health datasets to enrich analysis.
## References
### ***data.humdata.org***
***(https://data.humdata.org/dataset/dhs-data-for-kenya?force_layout=desktop)***

# Crime-Analysis-of-LAPD
# Crime Data Analysis – Los Angeles (2020–2023)

A comprehensive exploratory and statistical analysis of crime data from Los Angeles using R, Tableau, and public datasets. This project uncovers crime trends across time, geography, crime types, and victim demographics to guide resource allocation and public safety strategies.

## 🧠 Objectives

- Identify **most common crimes**, weapon use, and victim demographics
- Analyze **temporal patterns**: year, month, hour trends in crime rates
- Explore **geographic hotspots**: which areas have highest crime incidents
- Perform statistical testing (Chi-square) and regression to evaluate **correlations and predictors**

## 🛠 Tools & Technologies

- **Languages**: R  
- **Visualization**: Tableau Public  
- **Techniques**: Data Cleaning, Exploratory Data Analysis (EDA), Chi-Square Testing, Best Subset Regression

## 🔍 Key Features

- 📊 **Yearly Crime Trends**: Peak in 2022 with a notable drop in 2023
- ⏰ **Hourly Patterns**: Crime peaks at noon and remains high until 6 PM
- 📍 **Hotspot Mapping**: Central and 77th Street areas have the highest crime rates
- 🔫 **Weapons Analysis**: Strong-arm force most common; raises concern on physical altercation trends
- 💥 **Crime Type Analysis**: Vehicle theft and assault dominate the city crime profile
- 🧠 **Chi-Square Test**: Proves a strong correlation between crime type and location (p < 2.2e-16)
- 📈 **Best Subset Regression**: AREA, TIME.OCC, Crm.Cd, Premis.Cd, and Weapon.Used.Cd are key predictors for victim age

## 📈 Sample Insights

- **Crime Count by Year**:
  - 2022 had the highest count (233,692 cases)
  - Decline observed in 2023 possibly due to new policy interventions
- **Seasonal Trends**:
  - Peak months: January & May (~72,800 cases)
  - Lowest: August–October
- **Gender Trends**:
  - Male victims most common; large proportion of "Unknown" gender entries hint at reporting gaps

## 📊 Visualizations

- Time series and heatmaps (crime by hour, month, year)
- Bar plots (top crimes, weapon use, area-wise crime count)
- Geographic dashboards via Tableau: [🔗 Dashboard Link](https://public.tableau.com/app/profile/neer.bhanushali8627/viz/Crimedataanalysis_17418829609230/CrimeDataAnalysisDashboard?publish=yes)

## 💡 Recommendations

- Deploy **additional law enforcement** in Central, Pacific, and 77th Street zones
- Introduce **community-based crime prevention** during peak crime hours (12 PM – 6 PM)
- Focus on **weapons policy enforcement** to reduce physical altercations
- Investigate **2023 decline** in crime for replicable best practices

## 🔗 References

- Dataset: [Kaggle – LA Crime Data 2020–2023](https://www.kaggle.com/datasets/venkatsairo4899/los-angeles-crime-data-2020-2023/data)
- Stepwise Regression: [Statistics by Jim](https://statisticsbyjim.com/regression/guide-stepwise-best-subsets-regression/)


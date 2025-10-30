# The Relationship Between Social Well-Being and Crime: A Cross-Country Analysis of Happiness, Education, and Health Indicators

## Introduction
This project investigates how social and economic well-being factors such as happiness, education, and life expectancy influence crime perception across countries. Using international data from Kaggle and the World Bank, it analyzes whether higher education levels, longer life expectancy, and greater happiness contribute to safer societies. The goal is to uncover which social indicators best explain global differences in crime rates.

---
## Motivation / Problem Definition
Crime is not only a legal concern but also a mirror of a nation’s social and economic well-being. Education, health, and happiness are often considered key factors that can reduce criminal activity, yet the nature of these relationships varies widely across regions and cultures. This project seeks to uncover whether societies with higher levels of education, stronger health outcomes, and greater happiness tend to experience lower crime rates. By quantifying these links, the study aims to highlight how social development and overall well-being can contribute to building safer and more stable communities.

---
## Research Questions / Hypotheses
1- To what extent does a higher education rate contribute to a reduction in crime perception across countries?

2- Is there a significant negative relationship between happiness levels and the crime index?

3- How does life expectancy, as an indicator of overall health and social well-being, influence crime levels?

4- Among the key social indicators happiness, education, and health  which exerts the strongest impact on reducing crime globally?

---
## Data Sources
**The datas have been used:**  
The datas are for 2022 and the other years will be not be taken into account.
### 1.World Crime Index:
 - Provides global estimates of perceived crime and safety levels based on public surveys. It measures how safe people feel in their countries rather than official crime rates, making it suitable for cross-country comparisons.
 - https://www.kaggle.com/datasets/ahmadjalalmasood123/world-crime-index?select=World+Crime+Index+.csv
### 2.World Happiness Report 2022:
 - Ranks countries by citizens’ life satisfaction scores from the Gallup World Poll, influenced by factors like income, health, freedom, and social support. It is widely used to assess well-being and quality of life globally.
 - https://www.kaggle.com/datasets/mathurinache/world-happiness-report?resource=download&select=2022.csv
### 3.World Bank Education Data:
 - Provides education indicators sourced from UNESCO’s UIS API, including primary school enrollment rates. The data reflect educational access and participation across countries.
 - https://data.worldbank.org/indicator/SE.PRM.ENRR
### 4.World Bank Life Expectancy Data:
 - Derived from UN and Eurostat demographic statistics, estimating average life expectancy at birth for each country. It serves as a key indicator of national health and living standards.
 - https://data.worldbank.org/indicator/SP.DYN.LE00.IN?end=2023&most_recent_year_desc=true&start=1960



---
## Methodology / Data Preparation Plan
### Data Collection:
 - Datasets are obtained from Kaggle and the World Bank, including global indicators for happiness, education, life expectancy, and crime levels. All files are downloaded in CSV format and imported into Python for processing.

### Data Cleaning:
- Country names are standardized to ensure consistency across datasets. Missing values are handled through median or regional mean imputation, and irrelevant columns are removed to maintain analytical clarity.

### Data Integration:
- The datasets are merged using the common variable Country, forming a unified dataset containing social and economic indicators alongside crime perception scores. Only countries with complete key variables are retained for analysis.

### Feature Engineering:
 - After merging all datasets, the variables including happiness, education rate, life expectancy, and crime index  will be standardized to a common 0–1 scale to allow fair comparison across indicators. Additional derived metrics, such as the education-to-crime ratio and happiness-to-crime ratio, will be generated to capture the relative impact of social well-being on crime levels. Finally, each country will be categorized by region (for example, Europe, Asia, or Africa) to enable regional comparisons and identify broader geographic patterns in the data.


---
# Analysis Plan

### Statistical Analysis:
 - Conduct correlation and regression analyses to measure how happiness, education rate, and life expectancy affect the crime index. Use statistical tests such as Pearson correlation and multiple linear regression to identify significant relationships between the variables.

### Comparative Analysis:
 - Compare regional differences (e.g., Europe vs. Asia) to observe how development level influences crime perception. Examine whether higher education or happiness levels consistently correspond to lower crime rates across different regions.

### Visualization:
 - Use scatter plots and line graph to display correlations among variables, and regression plots to illustrate how changes in education, health, and happiness relate to variations in crime levels. Choropleth maps will be created to visualize global patterns in crime perception.


---
# Expected Outcomes / Deliverables

This project aims to provide data-driven insights into how social well-being indicators happiness, education, and health influence global crime perception.

**Expected findings include:** 

 - Quantified correlations showing that higher education and happiness levels are linked to lower crime indices.

 - Statistical evidence that life expectancy  also contributes to reduced crime perception.

 -  Visual patterns across regions illustrating that developed countries tend to have safer environments compared to developing ones.

 -  Regression-based conclusions identifying education and happiness as the strongest predictors of safety, revealing how social progress can reduce perceived crime globally.

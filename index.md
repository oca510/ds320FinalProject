# DS320 Final project
### Team Members:

Kebei Yu

Yulun We

Chaolong Shi

### Background
There are hundreds of different national and international university ranking systems like US News and QS. Ranking of universities are affected by a large number of factors. And it is a difficult and controversial practice ranking universities. For both universities and future students, the world rank of top 200 is an important benchmark. 

### Objective
The problems we hope to solve are which factors and models are better predictors to predict whether a university is top 200 or not. We break down the factors into three groups: internal factors, external factors and mixed factors. 

### Methodology
1. Use data integration techniques to combine data from different sources.
2. Classify features into three groups. (graph1)
3. Use machine learning such as decision tree,  linear regression to perform analysis on the data and output results for discussions. 
4. Use cross-validation methods to test and evaluate the models, and choose the best models. 

## Part1: Data Preparation
### Data sources
**University Ranking Data**

University Ranking data were published by The Center for World University Rankings (CWUR) in 2019.
Sources: The Center for World University Rankings (CWUR)
https://www.kaggle.com/mylesoneill/world-university-rankings/download

**University Information Data**

University Location Data is a dataset that contains locations and university and College.
Sources: Private

**Education data**

This data contains the education level data from the American Community Survey for adults 25+. Counts are broken down by sex. And there are 5-year estimates shown by tract, county, and state boundaries.
Sources: U.S. Census Bureau’s American Community Survey (ACS) 2016-2020 5-year estimates, Table(s) B15002 https://services.arcgis.com/P3ePLMYs2RVChkJx/arcgis/rest/services/ACS_Educational_Attainment_Boundaries/FeatureServer

**Population data**

This data provides boundaries for the States of the United States in the 50 states and the District of Columbia. And the attribute fields include estimated 2017 total population.  Sources: Esri, TomTom, U.S. Department of Commerce, U.S. Census Bureau https://services.arcgis.com/P3ePLMYs2RVChkJx/arcgis/rest/services/USA_States_Generalized/FeatureServer

### Data cleaning
* Missing value check: none
* Lower case for future matching
* String revising : delete ‘county’, replace state full name to abbreviation
* Filter year: use the latest info, only us universities

### Data Integraion
* Merge university info to university rank
* Merge education data to demographic data
* Merge local demographic data to university rank(county level)


## Part2: Model Analysis

## Part3: Findings and Limitations

### Conclusion


#### Link to Kaggle Profile:https://oca510.github.io/320html/

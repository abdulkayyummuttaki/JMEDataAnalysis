# Data Analysis on Joint Child Malnutrition Estimates (JME)
# Levels and Trends – 2023 edition

## Introduction

The JME includes estimates of prevalence and numbers affected for stunting, overweight, 
wasting and severe wasting among children under five years of age at country, regional 
and global levels. Global, regional and country annual trends from 2000-2022 are 
available for stunting and overweight.

**Stunting** refers to a child who is too short for his or her age. Children affected by 
stunting can suffer irreversible physical and cognitive damage accompanying stunted 
growth. The devastating consequences of stunting can last a lifetime and even affect 
the next generation. 

Globally in 2016, 22.9% or 154.8 million children under 5 years of age suffered from child stunting, 
defined by a low height-for-age (8). Stunting is measured by a height-for-age z-score of more 
than 2 standard deviations below the World Health Organization (WHO) Child Growth Standards 
median (9), showing a restriction of a child’s potential growth (10)

References:
	https://www.who.int/news/item/19-11-2015-stunting-in-a-nutshell
 
 	https://www.who.int/multi-media/details/stunting-in-a-nutshell-chapter1#
  
 

**Wasting** refers to a child who is too thin for his or her height. Wasting results from 
recent rapid weight loss or the failure to gain weight. A child who is 
moderately or severely wasted has an increased risk of death, but treatment 
is possible.

**Overweight** refers to a child who is too heavy for his or her height. This form of malnutrition 
results when energy intakes from food and beverages exceeds children’s energy 
requirements. Being overweight increases the risk of diet-related noncommunicable diseases 
later in life.

**What do these indicators tell?**

The indicators stunting, wasting, overweight and underweight are used to measure nutritional imbalance; such imbalance results in either undernutrition (assessed from stunting, wasting and underweight) or overweight. Child growth is internationally recognised as an essential indicator of the population's nutritional status and health.

These indicators are defined as follows: 

- stunting - height-for-age <-2 SD of the WHO Child growth standards median;
- wasting - weight-for-height <-2 SD of the WHO Child growth standards median; and
- overweight - weight-for-height >+2 SD of the WHO Child growth standards median.;
- underweight - weight-for-age <-2 standard deviations (SD) of the WHO Child growth standards median;

The Joint Child Malnutrition Estimates (JME) released in 2023 reveal insufficient progress 
to reach the 2025 World Health Assembly (WHA) global nutrition targets and SDG. 

+  Identify the number of deaths and affected due to mall nutrition.
+  Which countries are affected most by child nutrition?
+  How price inflation affects children's growth.
+  Malnutrition and country's population proportion. 

**Wasting and severe wasting**
Identify the trends in wasting in each country.

**Overweight**
Compare the overweight and underweight in each country.

Only about one-third of all countries are ‘on track to halve the number of children affected
by stunting by 2030, and assessment of progress to date has not been possible for about one-quarter 
of countries. 

## Data Source

Data is downloaded from UNICEF, WHO and World Bank inter-agency team. These teams update the Joint Child 
Malnutrition Estimates (JME) every other year. 

The JME includes estimates of prevalence and numbers affected by stunting, overweight, wasting and severe 
wasting among children under five years of age at country, regional and global levels. 


***Data Source:*** https://data.unicef.org/resources/dataset/malnutrition-data/

The Joint Malnutrition Estimates Working Group develops the following databases:	
+  Country Level Modeled Estimates Proportion, Numbers Affected (Stunting, Overweight)
+  Regional Level Modeled Estimates, Proportion and Numbers Affected (Stunting, Wasting and Overweight)
+  Country Level Survey Estimates, National (Stunting, Wasting, Severe Wasting, Overweight, Underweight)
+  Country Level Survey Estimates, National and Disaggregated (Stunting, Wasting, Severe Wasting, Overweight, Underweight)
+  Country Level Estimates, Overlapping Malnutrition (Stunted only, wasted only, overweight only, stunted and wasted, stunted and overweight, free from stunting, wasting or overweight)	

**Estimate Type**	The source of the estimate, whether as reported, reanalyzed, etc.			
-  Reanalyzed	Dataset has been obtained, standardized and reanalyzed to conform to the definition. Lower and Upper
-  Confidence limits are based on a 95% confidence level
-  External Reanalysis	Dataset reanalyzed by external partners
-  Reported	Point Estimate, and when available, other information, including sample size, Lower and Upper Confidence limits, are based on results from the report
  
Point Estimate:	The prevalence of wasting (moderate and severe) in the population
+  Lower Limit:	95% lower confidence interval of the point estimate
+  Upper Limit:	95% upper confidence interval of the point estimate
+  Sample size:	The weighted sample size, which the point estimate is based on			

Background Characteristics	Where available, the point estimates and other parameters are presented by a variety of background characteristics including

(i) sex (male and female)
(ii) area of residence (urban and rural)
(iii) wealth quintiles (based on asset-based wealth scores)
(iv) Mother's education
(v) Alternate wealth breakdowns (i.e. not quintiles)
(vi)  geographic area of residence.



+  National	
+  Sex	
+  Residence	
+  Age Group	
+  Wealth Quintile	
+  Wealth Quintile Grouping	
+  Mother's Education	
+  Area / Wealth Quintile	
+  Area / Wealth Quintile Grouping	
+  Sex / Age Group	
+  Subnational Region	

## Folder Structure
01 Project Management: Contains document analysis process and results.
02 Data: Contains project-related dataset. It has two folders Original data set and processed data(filtered, pivoted) inside the prepared data
03 Scripts/Python: Scripts contain source code in Python, and the example folder contains time series and regression analysis code.
04 Analysis/Visualizations: Requires to save the images from the script. The task is pending
=====================================================================

## References

**UNICEF-WHO-The World Bank: Joint Child Malnutrition Estimates (JME) — Levels and Trends – 2023 edition**
The UNICEF, WHO, and the World Bank inter-agency team update the joint global and regional estimates of
malnutrition among children under five years every other year.

https://data.unicef.org/resources/jme-report-2023/
https://data.unicef.org/resources/dataset/malnutrition-data/
https://data.unicef.org/resources/unicef-who-world-bank-joint-child-malnutrition-estimates-2023-edition-interactive-dashboard-2/
https://data.unicef.org/topic/nutrition/malnutrition/

### Other resources further analysis
https://www.worldbank.org/en/programs/icp/brief/foodpricesfornutrition
Monthly Food Price Inflation Estimates By Country
https://datacatalog.worldbank.org/search/dataset/0060165
https://data.unicef.org/how-many/how-many-children-are-breastfed/
https://data.unicef.org/resources/undernourished-and-overlooked/


# Postnatal Depression During COVID-19: Impact of Demographic Factors
### Project Overview
This research project investigates the relationship between demographic factors (maternal age, household income, and maternal education) and postnatal depression (measured by EPDS scores) in pregnant women during the COVID-19 pandemic. The study analyzes data from the Pregnancy during the COVID-19 Pandemic (PdP) project to understand how these demographic variables correlate with mental health outcomes.
Dataset

#### Source: Mental Health in the Pregnancy During COVID-19 dataset from the Pregnancy during the COVID-19 Pandemic (PdP) project
Collection Method: Survey-based data collection across Canada using random sampling
Sample Characteristics: Pregnant women with diverse demographic backgrounds
Key Variables:

#### Numerical Variables: Maternal Age, EPDS Scores
Categorical Variables: Household Income, Maternal Education, Mode of Delivery, NICU Stay



### Data Processing

#### Data Cleaning:

1. Replaced null values in the Maternal Age column with the median
2. Treated outliers in the age column using the IQR method
3. Converted numerical age data to categorical by dividing into five ranges
4. Consolidated education categories (e.g., "Less than High School" and "High School Education" into "High School or less")
5. Reduced household income categories from nine to five for better interpretability


#### EPDS Score Classification:

-0 to 6: "None or minimal depression"
-7 to 13: "Mild depression"
-14 to 19: "Moderate depression"
-20 to 30: "Severe depression"



### Statistical Methods
The following statistical methods were employed to investigate the relationship between demographic factors and postnatal depression:

#### Simple Linear Regression: Tested correlation between maternal age and depression levels
#### Pearson's Chi-square Test and Fisher's Exact Test: Examined associations between categorical variables and depression levels
#### Spearman Rank Test: Analyzed correlations between ordinal categorical variables
#### Ordinal Logistic Regression: Investigated the combined effect of all independent variables on depression levels

## Key Findings

### Age Impact: Younger maternal age was associated with higher postnatal depression risk (p < 0.001)
### Socioeconomic Factors: Lower household income and lower maternal education levels were significantly associated with higher EPDS scores (p < 2.2e-16)

###Correlation Strength:

#### Maternal Age: Weak negative correlation (rho = -0.0685, p < 0.001)
#### Household Income: Moderate negative correlation (rho = -0.1545, p < 0.001)
Maternal Education: Moderate negative correlation (rho = -0.143, p < 0.001)


### Overall Finding: All demographic factors demonstrated negative correlations with depression levels, with the null hypothesis rejected in favor of the alternative hypothesis that demographic factors correlate with postnatal depression during the COVID-19 pandemic

### Conclusion
This study demonstrates that younger age, lower household income, and lower maternal education were associated with higher levels of postnatal depression symptoms during the COVID-19 pandemic. These findings emphasize the need for targeted support for pregnant women at higher risk of postnatal depression, especially during times of crisis.

### Application
The findings can inform the development of:
-Targeted intervention strategies for vulnerable populations
-Mental health screening protocols that consider demographic risk factors
-Policy recommendations for maternal mental health support during public health emergencies

### Future Research Directions
-Explore additional factors contributing to postnatal depression
-Develop and test tailored intervention strategies based on demographic risk profiles
-Conduct longitudinal studies to assess long-term impacts of the pandemic on maternal mental health

### Dependencies
-R (statistical analysis)- Rstudio:R markdown
#### Required R packages:
-stats (for statistical tests)
-MASS (for ordinal logistic regression)
-dplyr (for data manipulation)
-ggplot2 (for visualizations)



### Project Team

-Nikhil Chowdary Gali, 
-Poorva Reddy Vanga, 
-Puja Darshana Mishra, 
-Ramya Keerthi Majji, 
-Sushruthi Panakanti.


### References

Arzamani, N., Soraya, S., Hadi, F., Nooraeen, S., & Saeidi, M. (2022). The COVID-19 pandemic and mental health in pregnant women: A review article. Frontiers in Psychiatry, 13, 949239. https://doi.org/10.3389/fpsyt.2022.949239
Harville, E. W., Wood, M. E., & Sutton, E. F. (2023). Social distancing and mental health among pregnant women during the coronavirus pandemic. BMC Women's Health, 23(1), 189. https://doi.org/10.1186/s12905-023-02335-x
Kaggle. (n.d.). Mental Health in the Pregnancy During the COVID-19. Retrieved from https://www.kaggle.com/datasets/yeganehbavafa/mental-health-in-the-pregnancy-during-the-covid-19
Using the EPDS as a screening tool. (n.d.). COPE; Centre of Perinatal Excellence (COPE). https://www.cope.org.au/health-professionals/health-professionals-3/calculating-score-epds/

### Contact
Ramya Keerthi Majji- rmajji@iu.edu

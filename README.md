# Statistical-Analysis-of-Californian-schools-Vaccination-

Performed Statistical analysis using bayesian and frequentist methods on the vaccination rates in California school districts and compared them to the USA vaccination rates for 38 years dated from 2017 and below. 
The end goal of this study was to improve the vaccination rates and also reporting by the californian districts by understanding the data and factors that are directly or indirectly related to thi

**Platforms/Sources:**

* RStudio and necessary packages
* packages : tidyverse, dlookr, visdat, DHARMa, gvlma, BayesFactor, psych

**Approach :**
* Started off with Exploratory Data Analysis using plots and tidyverse
* Performed feature engineering through logarithmic transformations of attributes which were heavily skewed
* Did Time series analysis to understand and see trends, and justified variations through some study.
* Used chisquared test and bayesian methods to understand the reporting rates of Public and Private Schools
* To understand the underlying factors that contributed to the reporting of vaccination rates, used Linear and Logistic regresions by studyinga nd analyzing the resiudals through plots, understanding multicollinearity and making changes, analyzing Q-Qplots(using DharMa tool)
  - Used Bayesian inference to verify the frequentist methods.
* Conducted Hypothesis testing using Dickey-Fuller-test and pearson's correlation test to get evidence
* From the analysis dine, provided suggestions for improvements of vaccination rates and reporting

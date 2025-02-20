# Understanding-the-Determinants-of-Life-Expectancy

## Overview
This project explores the determinants of life expectancy using statistical modeling techniques. The study examines the impact of health, economic, and social factors on life expectancy, using a dataset from the World Health Organization (WHO). Through multiple linear regression and other statistical techniques, this analysis provides insights into the most significant predictors of life expectancy and offers actionable recommendations for policymakers.

## Authors
- Adam Virani
- Anthony Obi
- Chris Atta Hawkson
- Maria Aidoo
- Ikeora Ekene

## Date Completed
December 1st, 2024

## Motivation
Life expectancy is a key indicator of population health and well-being. This project aims to:
- Identify the most influential predictors of life expectancy.
- Examine regional variations in life expectancy.
- Assess the impact of socioeconomic and health factors.
- Provide data-driven recommendations for policy interventions.

## Research Questions
1. Which health metrics (e.g., infant mortality, adult mortality, HIV incidence) have the largest impact on life expectancy?
2. How do socioeconomic factors (e.g., GDP per capita, schooling) contribute to life expectancy prediction?
3. What are the most influential predictors that can guide policy interventions?

## Dataset
- **Source:** World Health Organization (via Kaggle)
- **Time Period:** 2005–2015
- **Size:** 2,864 rows × 21 columns
- **Key Variables:**
  - Health Metrics: Infant mortality, under-five mortality, adult mortality, HIV incidence, immunization rates
  - Socioeconomic Factors: GDP per capita, schooling, economic status
  - Lifestyle Factors: Alcohol consumption, BMI, thinness prevalence
  - **Target Variable:** Life expectancy

## Methodology
1. **Data Preprocessing:**
   - Data cleaning and initial exploratory analysis.
   - Handling missing values and ensuring data consistency.
2. **Regression Modeling:**
   - Initial multiple linear regression with all predictors.
   - Multicollinearity check and variable selection (Variance Inflation Factor analysis).
   - Stepwise regression to refine the best additive model.
   - Exploration of interaction terms and higher-order terms.
3. **Model Assumptions & Validation:**
   - Checking for linearity, independence, homoscedasticity, and normality.
   - Addressing assumption violations (e.g., heteroskedasticity, influential points).
   - Final model evaluation using Adjusted R-squared and Residual Standard Error.

## Key Findings
- The best additive model explained **97.86% of the variance** in life expectancy.
- Significant predictors include:
  - **Health Factors:** Adult mortality, under-five deaths, HIV incidence
  - **Economic Factors:** GDP per capita, schooling, economic status
  - **Lifestyle Factors:** Alcohol consumption, BMI, thinness prevalence
- Interaction effects between economic and health variables played a key role in predicting life expectancy.
- The normality and homoscedasticity assumptions were violated, suggesting the need for alternative regression techniques (e.g., Weighted Least Squares).

## Conclusion
- **Living in a developed country improves life expectancy**, but this effect is moderated by under-five deaths, alcohol consumption, HIV cases, and GDP per capita.
- **Mortality rates impact life expectancy**, but the effect is complex and depends on other health and economic factors.
- **Policy Implications:**
  - Reducing child mortality and alcohol abuse while improving healthcare infrastructure could enhance life expectancy.
  - Addressing disparities in economic development can lead to better health outcomes.

## Future Work
- Implement **Generalized Linear Models (GLMs)** to account for assumption violations.
- Perform **k-fold cross-validation** for better model validation.
- Incorporate **more recent datasets** to analyze post-2015 trends.
- Explore **machine learning techniques** (e.g., Random Forest, Neural Networks) for improved prediction accuracy.

## References
1. Kaggle Dataset: [Life Expectancy (WHO) Fixed](https://www.kaggle.com/datasets/lashagoch/life-expectancy-who-updated/data)
2. Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani: *An Introduction to Statistical Learning with Applications in R.*


## Contact
For any questions or collaborations, please contact the authors via email or GitHub issues.


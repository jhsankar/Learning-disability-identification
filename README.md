# Learning-disability-identification
This repository contains an R-based analysis of disparities in learning disabilities across race, gender, and access-related factors 

# Who Gets Identified? Analyzing Equity in Learning Disability Diagnosis Across Race, Gender, and Access Barriers

## Project Overview
This project analyzes disparities in learning disability identification among children in the United States, with a focus on race, gender, and access-related barriers. Using data from the National Survey of Children’s Health (NSCH), the analysis explores whether children’s likelihood of being identified with a learning disability varies across demographic groups and whether factors such as insurance coverage, poverty, household language, and healthcare access help explain these differences.

The project was conducted in **R** using descriptive statistics, chi-square tests, and logistic regression models.

## Research Questions
- Are there racial and gender disparities in learning disability identification among children in the United States?
- Do socio-economic and household factors such as health insurance, poverty, household language, and metro status help explain these disparities?
- Do race and gender interact in ways that suggest compounded inequities in identification?

## Data Source 
- National Survey of Children’s Health (NSCH), U.S. Census Bureau and Maternal and Child Health Bureau

## Methods
The analysis was completed in three stages:
1. **Descriptive statistics** to summarize learning disability prevalence across demographic subgroups
2. **Bivariate analysis** using chi-square tests to examine associations between identification, race, and sex
3. **Multivariate logistic regression** to estimate the likelihood of identification while controlling for access-related and household-level factors

## Tools Used
- **R**
- `dplyr`
- `janitor`
- `ggplot2`
- `stats` (`glm` for logistic regression)

## Key Findings
- Learning disability identification varies significantly across racial groups.
- Gender differences are also statistically significant.
- After controlling for access-related factors, male children had higher odds of identification.
- Insurance coverage, poverty level, and unmet healthcare needs were important predictors of identification.
- The findings suggest that both need and access shape who gets diagnosed, pointing to possible inequities in screening and referral systems.

## Repository Structure
```text
learning-disability-identification/
├── R scripts/
├── report/
├── README.md

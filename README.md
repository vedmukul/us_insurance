# U.S. Medical Insurance Costs Analysis - Detailed Overview

## Introduction
This project is a detailed analysis of the U.S. Medical Insurance Costs dataset. The objective is to uncover the relationships between various factors such as age, BMI, smoking status, and the number of children, and their impact on insurance charges. The analysis is performed using statistical and machine learning techniques to derive meaningful insights.

## Data Description
The dataset comprises 1338 entries and includes the following columns:
- Age: The age of the individual.
- Sex: The gender of the individual.
- BMI: Body Mass Index.
- Children: Number of children/dependents.
- Smoker: Smoking status of the individual.
- Region: The residential area of the individual in the US.
- Charges: Individual medical costs billed by health insurance.

## Libraries Used
The analysis was conducted using Python, with the following key libraries:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For creating static, interactive, and animated visualizations.
- `seaborn`: For high-level interface for drawing attractive and informative statistical graphics.
- `sklearn`: For machine learning and predictive modeling.

## Problems Addressed
The project explores and tests several hypotheses related to the impact of demographic and health factors on insurance charges. Specific focus areas include:
- The effect of age on insurance charges.
- The relationship between BMI and insurance charges.
- The impact of smoking on insurance costs.
- The influence of the number of children on insurance charges.

## Conclusion and Key Findings
Our analysis leads to the following conclusions:
1. **Age and Insurance Charges:** A significant positive correlation exists between age and insurance charges, indicating higher charges with advancing age.
2. **BMI and Insurance Charges:** Higher BMI is strongly associated with increased insurance charges.
3. **Smoking and Insurance Charges:** Smoking status is a critical determinant of insurance costs, with smokers facing substantially higher charges than non-smokers.
4. **Children and Insurance Charges:** The number of children contributes to a mild increase in insurance charges.
5. **Predictive Modeling:** Demographic and health factors can effectively predict insurance charges, as evidenced by the high R-squared value in our regression model.

## Graphs and Visualizations Supporting Findings

The following visualizations are included to support our findings:
- **Age Distribution**: ![Age Histogram](https://github.com/vedmukul/us_insurance/blob/main/age_histogram.png)
- **BMI vs. Charges (colored by smoker status)**: ![BMI vs. Charges Scatter Plot](https://github.com/vedmukul/us_insurance/blob/main/bmi_vs_charges_scatter.png)
- **Total Insurance Charges by Region:** This graph illustrates how total insurance charges vary across different regions, highlighting regional disparities in insurance costs.
  ![Total Insurance Charges by Region](https://github.com/vedmukul/us_insurance/blob/main/avg_charges_by_region.png)
- **Average Insurance Charges by Gender and Smoker Status:** This graph compares insurance charges between genders, segmented further by smoker status, to show gender-specific trends in insurance costs.![Gender Charges vs Smokers Status](https://github.com/vedmukul/us_insurance/blob/main/avg_charges_by_gender_smoker.png)
- **Average Insurance Charges by Age Group:** This graph displays insurance charges across different age groups, providing insights into how insurance costs correlate with age.
  ![Average Insurance Charges by Age Group](https://github.com/vedmukul/us_insurance/blob/main/avg_charges_by_bmi_smoker.png)
- **Insurance Charges by BMI and Smoking Status:** This scatter plot explores the relationship between BMI and insurance charges, with a focus on the impact of smoking status.![Insurance Charges by BMI and Smoking Status](https://github.com/vedmukul/us_insurance/blob/main/bmi_vs_charges_scatter.png)
-
These insights provide a comprehensive understanding of the factors influencing medical insurance costs and can assist stakeholders in informed decision-making.

---

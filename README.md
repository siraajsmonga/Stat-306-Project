# STAT 306 Project: Analysis of University Rankings

## Project Overview
This project investigates factors influencing global university rankings using data from the **World University Rankings** dataset. The study focuses on universities in Canada, the United States, and the United Kingdom, identifying variables that significantly impact rankings and developing predictive models.

## Dataset
- **Source**: [Kaggle - The World University Rankings 2016–2024](https://www.kaggle.com/datasets/raymondtoo/the-world-university-rankings-2016-2024)
- **Description**:
  - Contains data for **over 1,000 universities** across multiple years.
  - Evaluates universities based on metrics like teaching quality, research, citations, and international outlook.
  - Focused on Canada, the US, and the UK for this analysis.

## Key Findings
- **Significant Predictors**:
  - **Number of Students**
  - **Student-to-Staff Ratio**
  - **Proportion of International Students**
  - **Gender Ratio**
- **Location** (Canada, US, UK) was not a significant predictor of overall scores.
- The final model effectively predicted university rankings with high accuracy.

## Methodology
1. **Data Preprocessing**:
   - Filtered data to include universities in Canada, the US, and the UK.
   - Handled missing values and standardized variables for consistency.
2. **Exploratory Data Analysis**:
   - Visualized key variables using histograms, boxplots, and summary statistics.
   - Explored relationships between variables and overall university scores.
3. **Statistical Modeling**:
   - Used forward selection to identify the most impactful predictors.
   - Employed logistic regression and backward selection for model refinement.

## Results
- Universities with better **student-to-staff ratios** and a higher **international student percentage** ranked higher overall.
- The **gender ratio** and the **number of students** were also significant, with more balanced ratios positively correlated with rankings.
- The US had the highest number of universities represented in the dataset, followed by the UK and Canada.

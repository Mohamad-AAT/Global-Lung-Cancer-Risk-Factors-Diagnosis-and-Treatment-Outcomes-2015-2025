# Global-Lung-Cancer-Risk-Factors-Diagnosis-and-Treatment-Outcomes-2015-2025
Interactive dashboards analyzing global lung cancer patterns, risk factors, diagnosis stages, and treatment outcomes. Explore trends across regions, age groups, and clinical outcomes to gain quick insights into lung cancer data.

## 🔗 Quick Access to Dashboards

Each dashboard explores a different aspect of lung cancer data:

- [Global Overview Dashboard](https://public.tableau.com/views/GlobalLungCancerRiskFactorsDiagnosisandTreatmentOutcomes20152025/Dashboard1)
- [Risk Factors Analysis Dashboard](https://public.tableau.com/views/GlobalLungCancerRiskFactorsDiagnosisandTreatmentOutcomes20152025/Dashboard2)
- [Treatment Outcomes Dashboard](https://public.tableau.com/views/GlobalLungCancerRiskFactorsDiagnosisandTreatmentOutcomes20152025/Dashboard3)

## Project Overview
This Tableau project explores patterns in lung cancer risk factors, diagnosis stages, and treatment outcomes using a global patient dataset. The interactive dashboard visualizes relationships between demographic characteristics, lifestyle factors (like smoking and air pollution), and clinical outcomes, helping users understand trends across regions and populations.

## Key Objectives
- Identify common risk factors for lung cancer (smoking history, air pollution, occupational hazards, genetic factors)
- Examine the distribution of cancer stages at diagnosis to assess early vs. late detection
- Explore relationships between treatment modalities and survival outcomes
- Compare trends across demographic groups and geographic regions

## Data
- **Source:** Kaggle (global lung cancer dataset)
- **Preprocessing:** Cleaned and manipulated using Tableau “Groups” and calculated fields
- **Age Groups:**
  - Lower Incidence: <49 years old
  - Increasing: 50–64 years old
  - High Incidence: 65–74 years old
  - Very High Incidence: >74 years old

## Analysis
- Statistical analysis was performed in Excel: Normality tests, Chi-square, T-Test, ANOVA, Bonferroni post hoc test

## Key Findings
- Patient cases increased from 81 to 189 (133% increase) between 2015 and 2025
- Most cases were NSCLC: 1,335 cases vs. 165 SCLC cases
- Highest case registration: Europe → Americas → Africa (least: 90 cases)
- Stage at diagnosis was significantly associated with gender, smoking status, tumor size, and cigarettes/day
- Case type was significantly associated with smoking status, tumor size, and years of smoking
- Surgery and surgery + chemotherapy were the main treatment modalities in stages 1 and 2, showing the highest survival rates
- Larger tumor size and metastasis were linked to lower survival
- Other treatment modalities showed mixed outcomes depending on cancer stage

## Dashboard Features
- Interactive visualizations of demographic and lifestyle factors vs. clinical outcomes
- Regional comparisons and trends
- Filters for cancer stage, cancer type, age group, gender, and WHO region

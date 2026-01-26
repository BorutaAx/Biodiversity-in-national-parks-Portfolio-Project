# Biodiversity in National Parks Analysis

## Project Overview
This project investigates biodiversity data from the National Parks Service. The goal is to analyze the conservation status of various species and identify patterns in endangered types across different parks. This was completed as part of my Data Science portfolio.

## Repository Structure
- biodiversity.ipynb: Main Jupyter Notebook containing all Python code, analysis, and visualizations.
- Biodiversity_Presentation.pdf: A high-level summary presentation of the project findings.
- Species_info.csv: Dataset containing species information and conservation status.
- Observations.csv: Dataset containing 7-day sighting records across parks.

## Final Presentation
**You can view the project slide deck here:** [View Presentation (PDF)](./Biodiversity_Presentation.pdf)

---

## Key Questions Addressed
1. Conservation Status Distribution: What is the current status of species across different biological categories?
2. Endangered Likelihood: Are certain types of species (e.g., Mammals, Birds) more likely to be endangered?
3. Statistical Significance: Are the differences in conservation status between species significant?
4. Park Observations: Which species are most common in specific parks?

## Technologies Used
- Language: Python 3
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scipy (Statistical Analysis)
- Environment: VS Code / Jupyter Notebooks
- Version Control: Git & GitHub

## Analysis Highlights
* Mammals & Birds: These groups show the highest protection rates (approx. 17% and 15%).
* Chi-Square Test: A statistical test was performed comparing Mammals and Birds. The resulting p-value of ~0.69 indicates that the difference in their protection rates is not statistically significant.
* Sample Size: For future studies on Foot and Mouth Disease, we determined a required sample size of 1,220 sheep to detect a 5% change in infection rates.

## Conclusions
The analysis reveals that while most species are currently under 'No Intervention', certain animal classes require closer monitoring. The integration of statistical testing ensures that our recommendations are based on mathematical evidence rather than just visual trends.

---
*Created by Marek Grobelny as part of the Data Science Journey.*
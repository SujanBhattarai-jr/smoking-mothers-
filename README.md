# Did Smoking Mothers Have Lowered Weight Children?

## Project Overview

This project analyzes the causal effect of maternal smoking during pregnancy on infant birth weight using a dataset from the National Natality Detail Files. The data contains information on births in Pennsylvania during 1989-1991, focusing on maternal smoking as the treatment variable and infant birth weight as the outcome variable.

The analysis involves:
- Initial comparisons between infants of smoking and non-smoking mothers.
- Addressing confounding variables using Propensity Score Matching (PSM) to balance the treatment and control groups.
- Re-estimating the effect of maternal smoking on infant birth weight post-matching.

The final results indicate that maternal smoking causally reduces infant birth weight by an average of 13 grams after accounting for confounding variables.

## Project Structure

```plaintext
.
├── README.md               # Project description and structure
├── SMOKING_EDS241.csv      # Data file containing the sample of births in Pennsylvania
├── analysis.Rmd            # Main analysis script written in R Markdown
└── featured_style_projects.css # Custom CSS for styling the HTML output

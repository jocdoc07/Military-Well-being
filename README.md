README: Alcohol and Drug Abuse Risk in Veterans
Data Source: ICPSR 38304 - Military Health and Well-Being

Project Overview
This repository contains data processing scripts, statistical analyses, and research outputs related to studying alcohol and substance abuse risk among U.S. veterans. The publicly available dataset ICPSR 38304 is utilized for this project. The focus is to identify the factors that most contribute to risk and to explore whether protective factors buffer these risks in alignment with the Buffering Hypothesis.

Objectives
- Obtain the current prevalence and patterns of alcohol and substance use among U.S. veterans.
- Perform data management, descriptive statistics, univariate and bivariate analysis on project-relevant variables.
- Assess multicollinearity using dendrograms and variance inflation factor (VIF) analysis.
- Conduct stepwise linear regression to determine each variable's contribution to risk and protective outcomes, incorporating literature-supported confounders.
- Evaluate the clinical relevance and effect sizes from regression analyses.
- Apply causal modeling techniques to assess causality versus association.
- Generate reproducible visualizations including forest plots, heat maps, and causal diagrams.
- Provide policy-relevant insights to inform and improve veterans’ behavioral health programming.

Dataset Information
- Title: Military Health and Well-Being Study, 2020 (ICPSR 38304)
- Source: https://www.icpsr.umich.edu/web/ICPSR/studies/38304
- Population: Veterans, 18 years and older
- Variables:
- Demographics: Age, Gender, Race, Income
- Protective Factors: Calling and Purpose, Community Engagement, Help-seeking Behavior, Military Identity, Quality of Life, Public Service Motivation, Overall Wellness
- Risk Factors: Combat Exposure, Daily Stress, Loneliness, Moral Injury, Self-Stigma, Suicidal Ideation, History of Traumatic Brain Injury
- Confounders: Based on established literature (e.g., Age, Gender, etc.)

Repository Structure
alcohol-substance-abuse-icpsr38304/
├── data/
│   ├── raw/                        # Original ICPSR data files
│   └── processed/                  # Cleaned and formatted datasets
├── notebooks/
│   ├── data_exploration.ipynb     # Initial data exploration and cleaning
│   └── buffering_model.ipynb      # Regression & causal buffering analysis
├── outputs/
│   ├── figures/                    # Plots, graphs, visualizations
│   └── tables/                     # Summary statistics, regression outputs
├── scripts/
│   ├── clean_data.R               # Data preprocessing scripts
│   └── regression_analysis.R      # Modeling and statistical analysis
├── README.md                      # Project overview and usage guide
└── requirements.txt               # Package dependencies
![image](https://github.com/user-attachments/assets/190d4255-bf21-4744-9a6b-8174defcb34e)

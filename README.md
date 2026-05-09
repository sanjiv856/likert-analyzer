# Analysis of privacy concerns related to third-party cookies using data from Likert Scale Questionnaires.

## Overview:
This project focuses on analyzing the privacy concerns of users regarding the acceptance of third-party cookies. The analysis is based on data collected through an online questionnaire survey, which utilized a Likert scale to measure participants' attitudes and perceptions.

Analyzes responses from an online questionnaire survey where participants rated their agreement with privacy-related statements on a 5-point Likert scale (Strongly Disagree to Strongly Agree).

The analysis pipeline covers:
- Data cleaning and preprocessing
- Exploratory data analysis with grouped bar charts and grid layouts
- One-way ANOVA and Tukey's HSD post-hoc tests
- Regression and correlation analysis
- Chi-squared tests
- Publication-ready visualizations

## Dataset Description:
The dataset used in this analysis contains responses from the online questionnaire survey. Each respondent was asked to indicate their level of agreement or disagreement with statements related to privacy concerns and their willingness to accept third-party cookies. The Likert scale, ranging from "Strongly Disagree" to "Strongly Agree," was used to capture participants' responses.

## Methodology:
The analysis involved various steps, including data preprocessing, exploratory data analysis (EDA), and statistical analysis. The data preprocessing phase focused on cleaning and preparing the dataset for analysis. EDA techniques were employed to gain insights into the distribution of responses and identify any trends or patterns. Statistical analysis techniques, such as hypothesis testing and correlation analysis, were used to assess the relationship between privacy concerns and the acceptance of third-party cookies.

## Results and Findings:
The analysis revealed valuable insights into users' privacy concerns and their willingness to accept third-party cookies. 
* Online privacy concerns, trust in a website, and incentives significantly influence user willingness to accept third-party cookies

## Sample Outputs

**Correlation matrix across survey dimensions:**

![Correlation Matrix](Figures/Correlation_Matrix.jpg)

**Response distribution by category:**

![Figure 1](Figures/Figure_1.jpg)

## Tools and Technologies Used:
1. R programming language
2. R packages: 
* library(tidyverse)
* library(RColorBrewer)
* library(grid)
* library(gtable)
* library(ggthemes)
* library(cowplot)
3. Statistical analysis techniques: 
* One way ANOVA
* Tukey's HSD
* Regression analysis
* Correlation analysis

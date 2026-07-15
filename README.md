# CBDC Awareness and Adoption Research

## Overview

This repository contains an empirical study examining public awareness, trust, and willingness to adopt Central Bank Digital Currency (CBDC).

The project investigates how behavioural, institutional, and informational factors influence adoption decisions for emerging financial technologies under conditions of uncertainty.

The study was conducted as part of a graduate-level research methodology project and implements a complete quantitative research workflow using Python.

---

## Research Questions

The project addresses four hypotheses:

### H1
Is there a significant difference in CBDC adoption willingness between males and females?

### H2
Does trust in the security of CBDC transactions influence willingness to adopt CBDC?

### H3
Do awareness and education levels predict CBDC adoption willingness?

### H4
Is there an association between education level and CBDC adoption categories?

---

## Dataset

- Survey responses from **79 participants**
- Cross-sectional survey design
- Likert-scale and categorical variables
- Variables include:

  - Gender
  - Age Group
  - Education Level
  - CBDC Awareness
  - Perceived Transaction Security
  - CBDC Adoption Willingness

---

## Methodology

The following statistical methods were employed:

| Method | Purpose |
|--------|---------|
| Independent Sample T-Test | Gender differences in adoption willingness |
| Pearson Correlation | Relationship between perceived security and adoption |
| Ordinary Least Squares Regression | Effect of awareness and education on adoption |
| Chi-Square Test | Association between education and adoption categories |

---

## Technology Stack

- Python
- pandas
- scipy
- statsmodels
- matplotlib
- seaborn

---

## Key Findings

### H1: Gender Differences
No statistically significant difference was found between males and females in CBDC adoption willingness.

**Result:** Not Supported

---

### H2: Trust and Adoption
Perceived security of CBDC transactions was positively associated with willingness to adopt CBDC.

- Correlation coefficient: **r = 0.35**
- p-value: **0.0014**

**Result:** Supported

---

### H3: Awareness and Education
Regression analysis showed that awareness and education jointly predict CBDC adoption willingness.

Interestingly, awareness demonstrated a statistically significant negative effect on adoption willingness, suggesting that greater familiarity with CBDC may increase skepticism or perceived risk.

Education exhibited a weaker and statistically insignificant effect.

**Result:** Partially Supported

---

### H4: Education Categories
No statistically significant association was found between education categories and CBDC adoption willingness.

**Result:** Not Supported

---

## Discussion

The findings suggest that trust and perceived security play an important role in shaping adoption decisions for emerging financial technologies.

The negative relationship between awareness and willingness highlights the importance of uncertainty, legitimacy, and perceived risk in innovation adoption processes.

These results contribute to the broader literature on digital currency adoption, financial innovation, and technology acceptance.

---

## Repository Structure

```text
.
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── CBDC_Adoption_Analysis.ipynb
│
├── data/
│   └── survey_responses.xlsx
│
├── figures/
│   ├── gender_ttest_distribution.png
│   ├── trust_correlation_plot.png
│   ├── regression_coefficients.png
│   ├── education_chisquare_plot.png
│   └── descriptive_statistics.png
```

## Future Work

Potential extensions include:

- Technology Acceptance Model (TAM)
- Unified Theory of Acceptance and Use of Technology (UTAUT)
- Logistic regression models
- Structural Equation Modelling (SEM)
- Cross-country comparative analysis

---

## Citation

If you use this repository for academic purposes, please cite appropriately.

---

## License

This repository is intended for academic and educational use.

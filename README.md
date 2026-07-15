# Statistical Methods in R 📈

**A collection of applied-statistics labs in R / R Markdown - probability, sampling distributions, inference, and regression - demonstrating the statistical foundations behind data science.**

![R](https://img.shields.io/badge/R-RMarkdown-276DC3?logo=r&logoColor=white) ![Topic](https://img.shields.io/badge/Topic-Applied%20Statistics-blue)
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## 🎯 What's here
Hands-on labs (OpenIntro-style) covering the core inferential-statistics toolkit, each as a reproducible **R Markdown** document with code, output, and written interpretation.

| Lab | Topic | Methods |
|---|---|---|
| `03_probability.Rmd` | Probability & simulation | random variables, simulation, distributions |
| `Part1_sampling_distributions.Rmd` | Sampling distributions | CLT, sampling variability |
| `2Part2_confidence_intervals.Rmd` | Confidence intervals | interval estimation, coverage |
| `inference_for_numerical_data.Rmd` | Inference (numerical) | t-tests, bootstrap, ANOVA |
| `16_inference_for_categorial_data2.Rmd` | Inference (categorical) | proportions, **chi-square** tests |
| `simple_linear_regression.Rmd` | Simple linear regression | OLS, diagnostics, R² |
| `multiple_regression.Rmd` | Multiple regression | multivariable models, model selection |
| `logistic_regression.Rmd` | Logistic regression | classification, odds ratios |
| `LAB_2_FNU_NIKKAT_AFRIN.Rmd` | Foundations lab | data wrangling & EDA in R |
| `Fun Nikkat Afrin.Rmd` | Exploratory mini-project | applied R practice |

Rendered PDFs/HTML of the labs are in [`rendered/`](rendered/).

## 💡 Why it's in my portfolio
Strong data science rests on statistical literacy. These labs show I can **reason about uncertainty, test hypotheses rigorously, and build & diagnose regression models** in R - complementing the Python/ML projects elsewhere in my portfolio and rounding out the toolset (Python · SQL · R · Cloud · BI).

## ▶️ How to run
```r
# In R / RStudio:
install.packages(c("tidyverse", "openintro", "infer", "broom"))
rmarkdown::render("labs/simple_linear_regression.Rmd")   # or knit any lab in RStudio
```

## 🛠️ Tech stack
`R` · `R Markdown` · `tidyverse` · `ggplot2` · hypothesis testing · regression · statistical inference

---
*Coursework labs from Computational Mathematics / Statistics, organized as a reproducible R portfolio. Duplicate files removed.*

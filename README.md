# SCAP Score: Predicting Complicated Acute Appendicitis 🚀

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

This repository contains the source code, statistical modeling scripts, and web application deployment files for the **SCAP (Score for Complicated Acute Appendicitis Prediction)** system. The model integrates clinical parameters (AIR score) with Computed Tomography (CT) imaging features to stratify the risk of complications in acute appendicitis patients.

## 🌐 Live Web Application (Clinical Tool)
The SCAP model has been successfully digitized into interactive web applications, allowing clinicians to perform rapid risk stratification in the emergency department.

* 🚀 **[SCAP Next.js Version (Recommended)](https://scap-app.vercel.app)**: Production-ready web app built with modern Next.js. Highly optimized for mobile devices and clinical workflows.
* 📊 **[R Shiny Prototype](https://dr-nguyen-scap-score.shinyapps.io/SCAP/)**: The original prototype version used for algorithmic testing and statistical visualization during the research phase.

## 🔒 Data Privacy & Ethical Compliance
In strict compliance with medical ethics and patient privacy regulations, the raw clinical dataset is **not publicly available** in this repository. All sensitive patient health information (PHI) is securely managed and encrypted within the hospital's internal REDCap system. 

## 📂 Source Code & Interactive Reports

To facilitate peer review and ensure full methodological transparency, the statistical outputs are provided in two formats:

*   📊 **[Executive Visual Portfolio](https://phamthainguyen-md.github.io/Phu-Luc-Luan-Van-2026/SCAP_Portfolio.html)**: A streamlined report focusing on publication-ready figures, including Optimism-corrected DCA, Calibration plots (2000 Bootstrap resamples), and Combined ROC curves. *(Recommended for quick review)*.
*   📑 **[Full Statistical Appendix](https://phamthainguyen-md.github.io/Phu-Luc-Luan-Van-2026/Phu_Luc_VII_SCAP.html)**: The comprehensive data analysis pipeline, encompassing clinical characteristic tables, multivariable logistic regression, inter-rater reliability (Cohen's Kappa & ICC), and predictive probability distributions.

**Raw Scripts**: The R Markdown source codes (`.Rmd`) for both reports are publicly available in this repository.

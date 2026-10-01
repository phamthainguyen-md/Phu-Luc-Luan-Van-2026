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

## 📂 Repository Structure
```text
├── R_scripts/            # Core R scripts for statistical modeling (Logistic Regression, Bootstrap, DCA)
├── WebApp_Nextjs/        # Source code for the Vercel-deployed web application
├── Shiny_Prototype/      # R Shiny app source code
└── README.md

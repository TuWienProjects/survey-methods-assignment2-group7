# Assignment 2 – Survey Development and Analysis  
**Course:** 105.708 Data Acquisition and Survey Methods (VU 2.0)  
**Semester:** Summer 2025  
**Group:** 7  
**University:** TU Wien  

---

##  Project Title  
**Impact of Artificial Intelligence as a Tool to Support Students' Learning Experience**

---

##  Overview  

This repository contains the full working solution for **Assignment 2** of the course *105.708 Data Acquisition and Survey Methods* at TU Wien. The assignment is divided into two parts:

- **Part A: Survey Development** – Creating survey questions and defining clear research objectives.
- **Part B: Survey Analysis** – Conducting exploratory, descriptive, and analytic analysis using R and presenting the results in an RMarkdown report and presentation slides.

All tasks are implemented in R with a clean, reproducible structure.

---

##  Objectives  

- Develop a valid and well-structured survey instrument  
- Collect both categorical and quantitative data  
- Analyze the responses using appropriate statistical methods  
- Interpret findings in the context of the defined research questions  
- Produce a clear and professional report and presentation

---

##  Research Questions  

1. Do students who use AI tools (like ChatGPT, Grammarly, etc.) complete academic tasks in less time while maintaining or improving the quality of their work compared to those who do not use AI tools?

2. Does the frequency of AI tool usage increase student motivation and engagement during study?

3. Do students who integrate AI tools into their study routines demonstrate better long-term retention of learned material?

---

##  Repository Structure

survey-methods-assignment2-group7/

├── data/ # Raw data files (e.g., group7.xlsx, survey question text)

├── results/ # Final outputs (.Rmd report, .pdf report, presentation slides)

├── analysis.R # Main analysis script or RMarkdown notebook

├── README.md # Project overview and usage instructions

└── .gitignore # Files and folders to exclude from Git


---

## 🛠 Tools and Packages Used  

- **R** (version ≥ 4.2.0)
- **RStudio**
- **R Packages**:
  - `tidyverse` – data manipulation and visualization  
  - `psych` – descriptive statistics and reliability analysis  
  - `lavaan` – CFA and model testing  
  - `semPlot` – CFA diagrams  
  - `likert` – Likert scale analysis and visualization  
  - `readxl` – importing Excel survey data  
  - `knitr`, `kableExtra` – report formatting and tables

Install all packages at once:
```r
install.packages(c("tidyverse", "psych", "lavaan", "semPlot", "likert", "readxl", "knitr", "kableExtra"))


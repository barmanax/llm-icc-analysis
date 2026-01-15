# LLM ICC Analysis

This repository contains the analysis code used for the paper **Assessing the Consistency of Large Language Models for Algorithm Evaluation**.
The notebook (`analysis.ipynb`) includes the full data-processing pipeline used in the study conducted in October 2024.

The analysis focuses on evaluating the consistency of several open-source LLMs when grading student algorithm-design responses. Each model was run across multiple trials, rubric scores were collected, and consistency metrics were computed. The notebook covers:

- Loading and cleaning the grading data  
- Computing descriptive statistics for each rubric category  
- Running ICC analysis using `pingouin`  
- Generating tables and visualizations used in the paper  

The dataset consists of **672 total trials** across four rubric categories:  
**algorithm design, completeness, clarity/readability, and logic**.  
All results produced in this notebook were used in the figures and tables of the paper.

This repository is mainly for archival and reproducibility purposes.  
If you’d like to extend the analysis or apply it to new LLM-generated grades, feel free to reach out or open an issue.


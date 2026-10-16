<p align="center">
  <h1>Neurocognitive Profiling</h1>
  <p><strong>A Multidimensional Analysis of Brain Volumes, Personality Traits, and Cognitive Performance</strong></p>
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python" alt="Python Data Analysis" />
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-orange?logo=googlecolab" alt="Google Colab" />
  <img src="https://img.shields.io/badge/Status-In%20Progress-yellow" alt="Project in progress" />
</p>

## Explore the Analysis

[Open the Jupyter Notebook](neurocognitive_analysis.ipynb) to explore the Python workflow, statistical analyses, and visualizations.

# Neurocognitive Profiling: A Multidimensional Analysis of Brain Volumes, Personality Traits, and Cognitive Performance

## Project Overview

This project explores the relationships between brain structural measurements, personality traits, and cognitive performance using Python.

The aim is to investigate multidimensional patterns in neurocognitive data through exploratory data analysis, statistical testing, data visualization, and, where appropriate, unsupervised machine learning.

## Research Questions

* How are brain structural measurements associated with cognitive performance?
* Is hippocampal volume associated with performance on a memory-related task?
* How are personality traits related to cognitive performance and psychological well-being?
* Can exploratory data-driven methods identify distinct neurocognitive profiles among participants?

## Tools and Technologies

* **Python** — Data analysis
* **Pandas and NumPy** — Data manipulation and preparation
* **Matplotlib and Seaborn** — Data visualization
* **SciPy** — Statistical analysis
* **Statsmodels** — Statistical modeling
* **Scikit-learn** — Data preprocessing and exploratory clustering, if implemented
* **Google Colab** — Notebook-based analysis

## Project Workflow

1. Data loading and quality assessment
2. Exploratory data analysis
3. Missing-value assessment and variable selection
4. Feature engineering
5. Correlation analysis
6. Multivariable regression, where appropriate
7. Exploratory neurocognitive profiling
8. Interpretation and communication of findings

## Preliminary Analysis

An initial Pearson correlation analysis examined the association between normalized hippocampal volume and `PicSeq_Unadj`.

* **Sample size:** 1,112 participants
* **Pearson correlation coefficient:** r = -0.037
* **p-value:** 0.223

The observed linear association was very weak and was not statistically significant at the conventional 0.05 significance level. This result does not establish that no relationship exists; further analyses should consider relevant covariates, measurement choices, and the limitations of the available data.

## Limitations

This is an observational analysis, so associations cannot by themselves establish causation. Structural brain measurements do not directly measure neuron counts or synaptic density. Any participant profiles identified through clustering should be interpreted as exploratory statistical groupings, not clinical diagnoses.

## Data Availability and Privacy

The notebook documents the analysis workflow. The underlying dataset is not included in this repository. Data should only be shared where the relevant license, consent, and data-use permissions allow it.

## Repository Structure

* `neurocognitive_analysis.ipynb` — Analysis notebook
* `README.md` — Project description, methods, and findings

## Author

An interdisciplinary researcher with a background in histology and embryology, developing practical experience in Python-based data analysis and statistical modeling.

![PCAanalizi](images/PCAanalizi.png)






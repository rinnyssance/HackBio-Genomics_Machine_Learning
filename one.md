# Exploring Genomics of Drug Sensitivity in Cancer (GDSC)

## Overview

The goal of Stage One is to explore the Genomics of Drug Sensitivity in Cancer (GDSC) dataset and investigate how genomic features may influence cancer drug response.

Rather than searching for a single “correct” answer, this project focuses on:

- Exploring biological patterns in the data
- Practicing data handling and cleaning
- Creating visualizations
- Asking meaningful scientific questions
- Interpreting findings clearly

---

# Project Goals

In this project, I explored:

- Drug sensitivity patterns across cancer cell lines
- Relationships between genomic features and drug response
- Potential effects of methylation, gene expression, and copy number alterations (CNA)
- Variability in drug effectiveness across cancer types

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Dataset

## Dataset Used

Genomics of Drug Sensitivity in Cancer (GDSC)

The dataset contains information related to:

- Cancer cell lines
- Drug response measurements
- Gene expression
- DNA methylation
- Copy number alterations (CNA)
- Drug targets and pathways
- Cancer types

---

# Biological Concepts Explored

## DNA Methylation

DNA methylation is a biological process that can reduce or silence gene activity. In cancer biology, abnormal methylation patterns may affect how cancer cells respond to treatment.

## Copy Number Alterations (CNA)

Copy number alterations occur when cancer cells gain or lose copies of genes. These changes may influence tumor growth and drug sensitivity.

## Drug Targets and Pathways

Cancer drugs often target specific proteins or signaling pathways involved in tumor growth.

Examples of important pathways include:

- MAPK pathway
- PI3K/AKT pathway
- Cell cycle pathways
- Apoptosis pathways

---

# Questions Investigated

Some of the questions explored during this project include:

1. Which drugs appear to be the most effective?
2. Which cancer cell lines are the most sensitive to treatment?
3. Are there patterns between methylation and drug response?
4. Do copy number alterations influence drug sensitivity?
5. Which pathways appear frequently among effective drugs?

---

# Data Exploration Workflow

## Step 1 – Loading the Dataset

The dataset was imported into Python using Pandas.

```python
import pandas as pd

gdsc = pd.read_excel("GDSC.xlsx")
```

---

## Step 2 – Exploring the Dataset

Initial exploration included:

- Viewing dataset dimensions
- Inspecting column names
- Checking missing values
- Understanding metadata

Example:

```python
gdsc.head()
gdsc.info()
gdsc.describe()
```

---

## Step 3 – Data Cleaning

Basic cleaning techniques included:

- Handling missing values
- Removing duplicates
- Standardizing data formats

---

## Step 4 – Visualization

Visualizations were created to better understand relationships in the data.

Examples include:

- Histograms
- Boxplots
- Scatterplots
- Correlation analysis

Example:

```python
import seaborn as sns
import matplotlib.pyplot as plt
```

---

# Key Takeaways

This project helped strengthen my understanding of:

- Bioinformatics workflows
- Exploratory data analysis
- Cancer genomics concepts
- Biological interpretation of data
- Data visualization techniques
- Scientific communication

It also demonstrated how computational methods can help researchers investigate complex biological questions related to cancer and drug response.

---

# Future Improvements

Future work could include:

- Machine learning models for drug response prediction
- More advanced statistical analysis
- Pathway enrichment analysis
- Genomic clustering techniques
- Predictive biomarker discovery

---

# Author

Erin Joel Moore

---

# Acknowledgments

- HackBio 
- GDSC Research Dataset
- Open-source Python scientific computing community

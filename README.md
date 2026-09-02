# Research Paper Citation Analysis

An end-to-end machine learning workflow for collecting, analyzing, and predicting research-paper citation impact using scholarly metadata from the OpenAlex API.

The project demonstrates a complete machine learning pipeline covering data collection, data cleaning, exploratory data analysis, feature engineering, regression modeling, hyperparameter tuning, model explainability, error analysis, and citation prediction.

---

## Kaggle Notebook

The original notebook is available on [Kaggle](https://www.kaggle.com/code/utkarshjain76/do-research-papers-have-an-impact). The notebook is in a descriptive and interactive format.

A fully generated dataset is also available on [Kaggle](https://www.kaggle.com/datasets/utkarshjain76/research-paper-citation-metadata). There are two versions of the dataset available, one is in Excel format for easy understanding of the generated dataset, and the other is in CSV format for machine use. 

The notebook named "Research Impact Intelligence: A Structured Bibliom" [Kaggle](https://www.kaggle.com/code/utkarshjain76/research-impact-intelligence-a-structured-bibliom) is an advanced analysis of the generated metadata.

---

## About OpenAlex

[OpenAlex](https://openalex.org/) is an open catalog of the global research system containing information about scholarly works, authors, institutions, sources, topics, and citations.

This project uses OpenAlex as the primary data source to collect research-paper metadata and investigate whether measurable characteristics of scholarly publications can provide useful signals for citation prediction.

---

## Project Overview

This project builds a complete machine learning pipeline for analyzing research-paper citation patterns.

The workflow:

- Collects scholarly metadata from the OpenAlex API
- Cleans and preprocesses the collected data
- Performs exploratory data analysis (EDA)
- Engineers features for machine learning
- Builds regression models for citation prediction
- Compares model performance
- Performs hyperparameter tuning
- Applies model explainability techniques
- Conducts prediction error analysis
- Generates citation predictions for a new research paper

The project is designed as a practical example of applying machine learning to **scholarly data analysis and research-impact prediction**.

---

## Research Question

> **Can scholarly metadata and measurable characteristics of research papers be used to predict their citation impact?**

The analysis also investigates which available paper characteristics contribute most strongly to citation predictions.

---

## Features

- OpenAlex API Integration
- Scholarly Metadata Collection
- Automated Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Regression Modeling
- Model Comparison
- Hyperparameter Tuning
- Model Explainability
- Prediction Error Analysis
- New Paper Citation Prediction
- Reproducible Machine Learning Workflow

---

## Machine Learning Workflow

```text
OpenAlex API
      │
      ▼
Data Collection
      │
      ▼
Data Cleaning & Validation
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Train / Test Split
      │
      ▼
Regression Models
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Model Evaluation
      │
      ▼
Explainability Analysis
      │
      ▼
Error Analysis
      │
      ▼
Citation Prediction
```
---

## Dataset

The dataset is generated from scholarly metadata collected through the [OpenAlex API](https://openalex.org/).

Depending on the stage of the pipeline, the collected information can include:

- Research paper information
- Publication year
- Citation count
- Authors
- Research concepts / topics
- Sources / journals
- Open-access information
- Other available scholarly metadata

The collected metadata is subsequently transformed into machine-learning-ready features.

---

## Data Analysis

The exploratory analysis focuses on understanding the structure and behavior of citation data.

Key analysis areas include:

- Citation-count distribution
- Feature distributions
- Missing values
- Data quality
- Correlations between variables
- Outlier identification
- Relationships between scholarly metadata and citation counts

This stage provides the foundation for feature selection and subsequent model development.

---

## Machine Learning

The project treats citation count as a regression problem.

The machine learning pipeline includes:

### Data Preprocessing

- Data cleaning
- Missing-value handling
- Feature transformation
- Feature preparation
- Train/test splitting

### Model Development

Multiple regression approaches are evaluated to identify models capable of capturing relationships between scholarly metadata and citation counts.

### Hyperparameter Tuning

Model parameters are optimized to investigate whether improved configurations can produce better predictive performance.

### Model Evaluation

Models are evaluated using appropriate regression metrics and compared to identify differences in predictive performance.

---

## Explainability

Model explainability is incorporated to understand the factors contributing to citation predictions.

Instead of evaluating models solely on predictive performance, the project investigates:

- Which features influence predictions
- Relative feature importance
- How individual characteristics affect model output
- Whether the learned relationships provide meaningful scholarly insights

This provides greater interpretability for a machine learning system operating on research-impact data.

---

## Error Analysis

Prediction errors are analyzed to understand the limitations of the developed models.

The analysis investigates:

- Large prediction errors
- Difficult-to-predict papers
- Outliers
- Systematic prediction patterns
- Differences between actual and predicted citation counts

Error analysis helps identify areas where additional data or improved modeling techniques may be required.

---

## New Paper Prediction

The completed pipeline can be applied to the metadata of a new research paper to generate an estimated citation outcome.

```text
New Research Paper
        │
        ▼
Metadata Extraction
        │
        ▼
Feature Transformation
        │
        ▼
Trained ML Model
        │
        ▼
Predicted Citation Impact
```
---

##  License

This project is licensed under the MIT License.

---

I am open to more collaborations and recommendations on this notebook.

# Research Paper Citation Analysis

An end-to-end machine learning workflow for collecting, analyzing, and predicting research-paper citation impact using scholarly metadata from the OpenAlex API.

The project demonstrates a complete machine learning pipeline covering data collection, data cleaning, exploratory data analysis, feature engineering, regression modeling, hyperparameter tuning, model explainability, error analysis, and citation prediction.

---

## Kaggle Notebook

The complete analysis is available as an interactive Kaggle Notebook.

**Kaggle Notebook:**  
[Research Paper Citation Analysis](https://www.kaggle.com/)

The notebook provides an interactive implementation of the complete workflow, from scholarly metadata extraction to model-based citation prediction.

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

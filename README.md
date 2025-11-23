# Student-stress-analysis
A Data-Driven Analysis of Sleep, Study Load, and Lifestyle Among Students.
# Student Stress Analysis 
*A Data-Driven Analysis of Sleep, Study Load, and Lifestyle Among Students*

## Project Overview

This project analyzes how sleep duration, study load, and lifestyle factors are related to student stress levels using a CSV dataset of students.  
The notebook/script explores patterns in the data, visualizes key relationships, and trains a simple machine learning model to predict stress level from sleep, study, and lifestyle variables.

## Dataset

- Format: `CSV` file (e.g., `student_stress.csv`)  
- Each row: one student  
- Example columns (change these to your real column names):
  - `Stress_Level` – target label (e.g., Low/Medium/High)
  - `Sleep_Hours` – average hours of sleep per night
  - `Study_Hours` – average study hours per day
  - Other lifestyle features – e.g., physical activity, screen time, caffeine intake, etc.

> Update this section with the real source (Kaggle/Mendeley/etc.), number of rows, and a short description of each important column.

## Project Structure

- `student_stress_analysis.py` – main Python script with:
  - Data loading and cleaning
  - Exploratory Data Analysis (EDA) plots
  - Correlation heatmap
  - Model training (Random Forest)
  - Evaluation metrics and feature importance
- `student_stress.csv` – dataset file (not included here if it’s large or external)
- `README.md` – project description and usage instructions

If you use a notebook instead of a script, rename accordingly (e.g., `student_stress_analysis.ipynb`).

## Installation

1. Clone or download this repository.  
2. Create and activate a virtual environment (optional but recommended).


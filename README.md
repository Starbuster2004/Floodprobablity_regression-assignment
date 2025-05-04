# 🌊 Flood Probability Regression Assignment

This project aims to **predict flood probabilities** using **regression techniques**, with a focus on **Ridge Regression**. By analyzing a dataset composed of environmental and human activity indicators, we estimate the likelihood of flood events. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and result visualization.

---

## 📑 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Workflow](#workflow)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## 🌍 Overview

Flooding is one of the most devastating natural hazards, causing extensive damage to life and property. Accurate prediction of flood probability is vital for **disaster preparedness** and **risk mitigation**.

This project uses **regression modeling**, particularly **Ridge Regression**, to predict flood probability based on various factors:

- **Environmental**: Monsoon Intensity, Topography Drainage, Climate Change, etc.
- **Human Activity**: Urbanization, Deforestation, Encroachments, etc.

---

## 📊 Dataset

The project uses three primary files:

- `train.csv`: Labeled data with features and target (`FloodProbability`).
- `test.csv`: Unlabeled data for prediction.
- `sample_submission.csv`: Submission format.

### Key Features

- `MonsoonIntensity`
- `TopographyDrainage`
- `ClimateChange`
- `Urbanization`
- `Deforestation`
- `Encroachments`
- **Target Variable**: `FloodProbability`

---

## 🧰 Dependencies

Install required libraries with:

```bash
pip install scikit-learn pandas matplotlib seaborn


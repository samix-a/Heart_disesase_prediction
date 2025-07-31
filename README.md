# Heart Disease Prediction

This repository contains a machine learning project to predict the likelihood of heart disease in patients using a logistic regression model. The project uses the [UCI Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease) and is implemented in Python using libraries such as pandas, numpy, and scikit-learn.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)
  
## Project Overview

Heart disease is a leading cause of death worldwide. Early prediction can help in timely intervention and treatment. This project aims to build a predictive model that can classify whether a person has heart disease based on various medical attributes.

## Dataset

The dataset used has 303 records with 14 features such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, and others. The target variable indicates the presence (1) or absence (0) of heart disease.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- (optional) Jupyter Notebook or Google Colab

## Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/samix-a/Heart_disesase_prediction.git
   cd Heart_disesase_prediction
   ```

2. **Run the notebook:**
   Open `Heart_Disease_Prediction_Project.ipynb` in Jupyter Notebook or Google Colab and follow the cells to load data, train the model, and make predictions.

3. **Make predictions:**
   You can input your own patient data in the notebook to predict the probability of heart disease.

## Model Details

- **Model Used:** Logistic Regression
- **Features:** 13 medical attributes
- **Performance:**
  - Training Accuracy: ~85.5%
  - Test Accuracy: ~80.3%

## Results

The logistic regression model achieves an accuracy of about 80% on test data, indicating a good baseline for heart disease prediction using clinical data.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

---

**Author:** [samix-a](https://github.com/samix-a)

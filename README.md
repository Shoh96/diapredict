# DiaPreSys
Diabetes Prediction System with python

# Diabetes Patients Analysis

## Overview
This project aims to diagnostically predict whether a patient has diabetes based on certain diagnostic measurements included in the dataset. The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. All patients in the dataset are females at least 21 years old of Pima Indian heritage.

## Dataset
The dataset includes the following columns:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- **Blood Pressure**: Diastolic blood pressure (mm Hg)
- **Skin Thickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **Diabetes Pedigree Function**
- **Age**: Age (years)
- **Outcome**: Class variable (0 or 1)

## Objective
The objective of this analysis is to explore the dataset, visualize relationships between features and the target variable (Outcome), and provide recommendations based on the findings.

## Files
- `DiaPreSys.ipynb`: Jupyter Notebook with the complete analysis.
- `diabetes.csv`: The dataset file.
- `requirements.txt`: List of required Python packages.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/diapredict.git
    ```

2. Navigate to the project directory:
    ```bash
    cd DiaPreSys
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook:
    ```bash
    jupyter notebook DiaPreSys.ipynb
    ```

## Visualizations
The project includes various visualizations such as pair plots, heatmaps, and scatter plots to understand the relationships between features and the Outcome variable.

## Recommendations
1. **Early Screening**: Women with higher Glucose levels and BMI should be screened regularly for diabetes.
2. **Lifestyle Interventions**: Patients with higher BMI should be encouraged to adopt healthier lifestyles to manage their weight and potentially reduce their risk of diabetes.
3. **Targeted Medical Attention**: Special attention should be given to patients with high Glucose and Insulin levels for early detection and management of diabetes.

## License
This project is licensed under the MIT License.

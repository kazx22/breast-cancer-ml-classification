# Medical Image Classification — Breast Cancer Diagnosis

This project focuses on applying machine learning techniques to classify breast cancer cases as **malignant** or **benign** using extracted medical imaging features from breast tissue samples.

The work was completed as part of the **Medical Image Classification module** at the University of South Wales.

## Project Overview

Advances in machine learning allow computer systems to assist medical professionals in disease diagnosis. This project uses the **Wisconsin Breast Cancer Diagnostic Dataset**, which contains numerical features extracted from breast cell nuclei images.

The objective was to develop and evaluate multiple machine learning models capable of accurately distinguishing between healthy and cancerous tissue samples using statistical analysis and predictive modelling.

## Dataset

The dataset includes measurements derived from medical images such as:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension

The dataset contains **569 samples and 32 features**, representing diagnostic characteristics of cell nuclei.

## Methodology

The project followed a complete machine learning pipeline:

### 1. Data Exploration
- Dataset inspection using Pandas
- Statistical summaries
- Distribution analysis using histograms
- Class balance visualization

### 2. Data Preprocessing
- Missing value detection
- KNN Imputation for missing data handling
- Outlier removal using IQR method
- Correlation analysis between features

### 3. Feature Engineering
- Label Encoding
- Feature Scaling using StandardScaler
- Train-test split (80% training / 20% testing)

### 4. Machine Learning Models

The following models were implemented and evaluated:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Neural Network (MLP)

## Results

Model performance comparison:

| Model | Performance |
|------|------------|
| Decision Tree | ~92% Accuracy |
| Random Forest | ~96% Accuracy |
| Support Vector Machine | ~97% Accuracy |
| Neural Network (MLP) | R² Score ≈ 0.838 |

SVM and Random Forest achieved the strongest classification performance with high ROC-AUC scores close to 1.

## Key Techniques Used

- Exploratory Data Analysis (EDA)
- KNN Imputation
- IQR Outlier Detection
- Feature Scaling
- Hyperparameter Tuning
- Confusion Matrix Evaluation
- ROC Curve Analysis

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Repository Structure

- Dataset preprocessing and analysis scripts
- Model training implementations
- Evaluation visualizations
- Coursework report

## Academic Context

University of South Wales  
MSc Computer Science  
Medical Image Classification Coursework

## Author

Kazi Alif  
GitHub: https://github.com/kazx22

## License

This project is licensed under the MIT License — see the LICENSE file for details.

# Phosphodiesterase-4D-Inhibitor-Prediction-Application-of-Lipinski-s-Rule-pIC50-Conversion-ML-MODELS
# Phosphodiesterase 4D (CHEMBL288) Inhibitor Prediction

## Overview
This project aims to predict the inhibition activity of Phosphodiesterase 4D (PDE4D) using the CHEMBL288 dataset. The study incorporates the application of Lipinski's Rule of Five for drug-likeness assessment, pIC50 conversion for standardizing the bioactivity values, and several machine learning models for data analysis.

## Project Goals
- **Predict** the inhibition activity of compounds against PDE4D.
- **Apply Lipinski’s Rule of Five** to filter potential drug-like molecules.
- **Convert IC50 values to pIC50** for consistent bioactivity representation.
- **Develop machine learning models** (Logistic Regression, Random Forest, K-Nearest Neighbors, LazyRegressor) to predict PDE4D inhibitor activity.

## Dataset
The dataset is sourced from the [ChEMBL database](https://www.ebi.ac.uk/chembl/), specifically the CHEMBL288 dataset. It contains bioactivity data for various compounds tested against the Phosphodiesterase 4D enzyme. Key features in the dataset include molecular descriptors and corresponding IC50 values.

### Key Steps:
1. **Lipinski's Rule of Five**: Applied to filter out molecules that don't meet the basic drug-like properties.
2. **pIC50 Conversion**: The IC50 values (in nM) were converted into pIC50 values (log scale) for better model performance.
3. **Data Preprocessing**: The dataset was cleaned and feature-engineered to extract relevant molecular descriptors.
4. **Machine Learning Models**: Implemented Logistic Regression, Random Forest, K-Nearest Neighbors, and LazyRegressor models to predict inhibitor activity. The models were trained and tested to evaluate their performance.

Requirements
Python 3.x
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
LazyPredict

### Project Structure
data/: Contains the cleaned dataset.
notebooks/: Jupyter Notebooks with code for data analysis, Lipinski's Rule application, pIC50 conversion, and machine learning model training.
models/: Pre-trained models and their evaluations.
requirements.txt: Python dependencies.

## Installation
To get started with this project, clone this repository and install the required libraries:

```bash
git clone https://github.com/SWAROOP-KUMAR18/PDE4D_CHEMBL288_Inhibitor_Prediction.git
cd PDE4D_CHEMBL288_Inhibitor_Prediction
pip install -r requirements.txt

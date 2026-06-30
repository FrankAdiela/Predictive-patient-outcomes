# Predictive Patient Outcomes Using Machine Learning

This project was completed as part of my MSc in Applied Artificial Intelligence and Data Analytics. It explores how machine learning can be used to predict patient outcomes using healthcare data.

The project involved preparing and analysing patient-related data, building predictive models, and evaluating model performance using appropriate machine learning metrics.

## Project Aim

The aim of this project was to investigate whether machine learning models could support the prediction of patient outcomes by identifying patterns in historical healthcare data.

## Dataset

The original dataset used for this project is not included in this repository.

During the MSc dissertation, the dataset was processed and transformed to create a modified dataset for machine learning analysis. This involved data cleaning, preprocessing and feature engineering to prepare the data for Logistic Regression and Random Forest modelling.

The repository is therefore intended to showcase the machine learning workflow, Python implementation, model development and evaluation process rather than provide a fully reproducible dataset package.

## Data Preparation

Data Cleaning Process

The healthcare dataset required preprocessing before machine learning could be performed.

The data preparation process included:

- Replacing invalid placeholder values ('?') with missing values (NaN)
- Assessing missing values across all variables
- Creating a processed dataset for modelling
- Generating additional synthetic patient features
- Exporting the cleaned dataset for downstream analysis

These preprocessing steps ensured the data was suitable for machine learning and demonstrated practical data preparation techniques commonly used in real-world analytical workflows.

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn

## Models Used

- Logistic Regression
- Random Forest Classifier

## Skills Demonstrated

### Data Engineering

- Data extraction
- Data transformation
- Dataset creation
- Data export
- Missing value handling
- Data quality assessment

### Data Analysis

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Cleaning
- Statistical Analysis

### Machine Learning

- Logistic Regression
- Random Forest
- Model Evaluation
- Classification Metrics
- ROC Analysis
- Confusion Matrix

### Programming

- Python
- Pandas
- NumPy
- Scikit-learn

## Project Workflow

1. Loaded patient encounter data containing hospital admission, medication and readmission variables.
2. Created additional synthetic patient-level features to support modelling.
3. Cleaned and prepared the dataset for classification.
4. Performed feature engineering and preprocessing.
5. Trained Logistic Regression and Random Forest models.
6. Evaluated model performance using classification metrics, confusion matrices and ROC curves.
7. Compared model performance and interpreted the results.

## Key Learning

This project strengthened my understanding of the full machine learning workflow, from data preparation through to model evaluation. It also helped me appreciate the importance of data quality, feature selection and responsible use of predictive analytics in healthcare-related contexts.

## Repository Contents

- `logistic_regression_and_random_forest_model.ipynb` — main machine learning notebook
- `README.md` — project documentation

## Author

Frank Adiela  
MSc Applied Artificial Intelligence and Data Analytics  
Aspiring Data Engineer / AI Engineer

# EEG-Seizure-and-Sleep-disorder-classification
# EEG-Based Classification of Seizure and Sleeping Disorders using Machine Learning

<img width="780" height="435" alt="image" src="https://github.com/user-attachments/assets/5af9ee05-6a12-45ab-a01d-f9a3ae01ee86" />


## Overview

This project focuses on the classification of seizure and sleeping disorders using Electroencephalography (EEG) biosignal data. EEG signals were preprocessed, analyzed, and transformed into meaningful features before training multiple machine learning models to classify neurological conditions.

The objective was to compare different machine learning approaches and identify the model that provides the best classification performance for EEG-based disorder detection.

---

## Project Information

**Project Duration**
July 2024 – November 2024

**Institution**
Shanmugha Arts, Science, Technology & Research Academy (SASTRA), Thanjavur

---

## Problem Statement

Manual analysis of EEG recordings is time-consuming and requires expert interpretation. Machine learning can assist clinicians by automatically identifying seizure and sleep disorder patterns from EEG signals, improving diagnostic efficiency and accuracy.

---

## Objectives

- Analyze EEG biosignal datasets.
- Preprocess EEG recordings to remove noise and artifacts.
- Extract relevant signal features.
- Train multiple machine learning models.
- Compare model performance.
- Identify the most effective classification model.

---

## Features

- EEG signal preprocessing
- Feature extraction
- Machine learning classification
- Performance comparison
- Model evaluation
- Healthcare-focused predictive analytics

---

## Dataset

The project uses EEG biosignal data containing recordings associated with seizure and sleeping disorders.

# Dataset

## Overview

This project uses the **Temple University Hospital (TUH) EEG Corpus** for seizure and sleep disorder classification.

The TUH EEG Corpus is one of the world's largest publicly available clinical EEG datasets and is widely used for research in biosignal analysis, machine learning, and neurological disorder detection.

---

## Dataset Source

**Temple University Hospital EEG Corpus (TUH EEG Corpus)**

Website:
https://isip.piconepress.com/projects/tuh_eeg/

---

## Dataset Access

The dataset is **not included** in this repository.

It was obtained through academic/research access from Temple University and is distributed under its own license and terms of use.

Please visit the official website to request or download the dataset if you have the appropriate access.

---

# Sample Dataset

The original EEG dataset used in this project is the **Temple University Hospital (TUH) EEG Corpus**, which is distributed under its own licensing terms and therefore cannot be included in this repository.

The file **sample_dataset.csv** is a **synthetic sample** created to demonstrate the expected input format for preprocessing and machine learning. It does **not** contain real patient data or records from the TUH EEG Corpus.

To reproduce the results, please obtain the original dataset from the official TUH EEG website and follow the preprocessing pipeline described in this repository.

Subject_ID,Session,Channel,Mean,Std_Dev,Variance,Skewness,Kurtosis,Delta_Power,Theta_Power,Alpha_Power,Beta_Power,Gamma_Power,Entropy,RMS,Peak_Frequency,Label
S001,1,Fp1,0.245,0.081,0.0066,-0.12,2.98,12.45,8.23,6.12,3.45,1.28,2.41,0.267,9.8,Seizure
S002,1,Fp2,0.198,0.075,0.0056,0.08,3.12,10.84,7.65,5.91,3.18,1.14,2.18,0.212,10.1,Normal
S003,1,C3,0.312,0.094,0.0088,-0.35,2.76,13.87,9.21,6.48,4.12,1.43,2.67,0.331,8.9,Sleep Disorder
S004,2,C4,0.276,0.086,0.0074,-0.18,3.01,12.13,8.54,6.35,3.82,1.31,2.46,0.289,9.5,Seizure
S005,2,O1,0.221,0.079,0.0062,0.11,3.18,11.27,7.94,5.88,3.36,1.22,2.27,0.236,10.3,Normal
S006,2,O2,0.304,0.092,0.0085,-0.29,2.83,13.54,9.03,6.51,4.08,1.39,2.61,0.323,8.8,Sleep Disorder
S007,3,T3,0.268,0.084,0.0071,-0.09,3.07,11.98,8.37,6.26,3.74,1.29,2.39,0.281,9.6,Seizure
S008,3,T4,0.214,0.078,0.0060,0.14,3.21,10.96,7.83,5.93,3.27,1.19,2.24,0.228,10.2,Normal
S009,3,F3,0.319,0.097,0.0094,-0.41,2.69,14.12,9.46,6.74,4.25,1.47,2.74,0.338,8.6,Sleep Disorder
S010,3,F4,0.283,0.088,0.0077,-0.21,2.94,12.39,8.69,6.41,3.91,1.35,2.52,0.296,9.3,Seizure


## Dataset Format

- EEG Signal Files (.edf)
- Patient Metadata
- Annotation Files

---

## Usage in this Project

The dataset was used for:

- EEG signal preprocessing
- Feature extraction
- Seizure classification
- Sleep disorder classification
- Machine learning model training and evaluation

---

## Note

Only the source code, preprocessing scripts, feature extraction pipeline, trained models (if permitted), and project documentation are included in this repository.

The original dataset has been excluded to comply with the dataset's licensing terms.

## Project Workflow

EEG Dataset
     ↓
Data Preprocessing
     ↓
Signal Cleaning
     ↓
Feature Extraction
     ↓
Train-Test Split
     ↓
Model Training
     ↓
Performance Evaluation
    ↓
Best Model Selection

---

## Data Preprocessing

- Missing value handling
- Signal normalization
- Feature scaling
- Data cleaning
- Feature selection

---

## Machine Learning Models

The following models were implemented and evaluated:

- Random Forest
- Support Vector Machine (SVM)
- Convolutional Neural Network (CNN)

---

## Model Evaluation Metrics

The models were compared using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC 

---

## Model Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|----------|-----------|--------|----------|
| Random Forest | XX% | XX | XX | XX |
| Support Vector Machine | XX% | XX | XX | XX |
| Convolutional Neural Network | XX% | XX | XX | XX |


## Best Performing Model

After evaluating all models, **[Best Model Name]** achieved the highest overall performance based on the evaluation metrics and was selected as the most effective classifier for this EEG dataset.

---

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- MNE 
---

## Repository Structure

```
Dataset/
│
Preprocessing/
│
Feature_Extraction/
│
ML_Models/
│
CNN_Model/
│
Results/
│
Images/
│
Documentation/
│
Presentation/
│
README.md
```

---

## Results

- Successfully preprocessed EEG biosignal data.
- Extracted meaningful signal features.
- Trained and evaluated multiple machine learning models.
- Compared Random Forest, SVM, and CNN for disorder classification.
- Identified the best-performing model for seizure and sleep disorder detection.

---

## Future Improvements

- Use larger EEG datasets.
- Apply deep learning architectures such as LSTM or Transformer models.
- Perform real-time EEG classification.
- Deploy the model as a web application.
- Improve model generalization using cross-validation and hyperparameter tuning.

---

## Skills Demonstrated

- EEG Signal Processing
- Biosignal Analysis
- Machine Learning
- Deep Learning
- Data Preprocessing
- Feature Engineering
- Model Evaluation
- Healthcare Analytics

---

## Author

**Haripriya K**

Biomedical Engineering Graduate

Machine Learning | Data Analysis | Python | Healthcare AI | Signal Processing

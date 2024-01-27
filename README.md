# Credit Card Fraud Detection

This project explores the use of different sampling techniques and machine learning models for credit card fraud detection. The goal is to evaluate the performance of various combinations of sampling methods and models to find the best approach for handling imbalanced datasets.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)

## Introduction

The project uses the following techniques and models:

### Sampling Techniques

1. RandomOverSampler
2. SMOTE
3. RandomUnderSampler
4. NearMiss (version=1, n_neighbors=5)
5. TomekLinks

### Machine Learning Models

1. Random Fores tClassifier
2. Support Vector Machine (SVM)
3. Decision Tree Classifier
4. Logistic Regression
5. Gaussian NB

## Installation

To run the code, you need to have Python and the required libraries installed. Use the following command to install the necessary libraries:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/NEMERO21/Sampling-Assignment.git
   ```
   
2. **Run the code:**
   ```bash
   python Sampling_Assignment.ipynb
   ```

## Results
The code generates accuracy results for different combinations of sampling techniques and machine learning models. The best sampling techniques for each model are also displayed.
![image](https://github.com/NEMERO21/Sampling-Assignment/assets/97607950/35e41f66-cd78-4f93-85cf-94860850fc8f)
![image](https://github.com/NEMERO21/Sampling-Assignment/assets/97607950/24cbe407-2486-40c7-bc33-6e2cba441174)
![image](https://github.com/NEMERO21/Sampling-Assignment/assets/97607950/cdb95062-eeba-4f70-b321-05a064a8d5d5)

## Dependencies
1. numpy
2. pandas
3. matplotlib
4. scikit-learn
5. imbalanced-learn
6. tabulate

Install the required dependencies using the following command:
```bash
pip install -r requirements.txt
```

<div align="center">
  <h1>Heart Disease Prediction</h1>
</div>


<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
    <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" />
    <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />
    <img src="https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white" />
    <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black" />
        <img src="https://img.shields.io/badge/seaborn-%23565E64.svg?style=for-the-badge&logo=seaborn&logoColor=white" />
    <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" />
    <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" />
    <img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white" />
    <img  src="https://img.shields.io/badge/Streamlit-%235F4690.svg?style=for-the-badge&logo=streamlit&logoColor=white" />

</div>
<br>



#### -- Project Status: In-Progress

LINK TO NOTEBOOK
LINK TO PREDICTION WEBSITE

# Table of Contents

## Objective
- I'll briefly describe the main goal of the project and potential impact. (3-6 Sentences)



## Usage
- talk about how to use streamlit app with gifs

## [Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)


**Attribute Information**
1.  Age: age of the patient [years]
2.  Sex: sex of the patient [M: Male, F: Female]
3.  ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
4.  RestingBP: resting blood pressure [mm Hg]
5.  Cholesterol: serum cholesterol [mm/dl]
6.  FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
7.  RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
8.  MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
9.  ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
10.  Oldpeak: oldpeak = ST [Numeric value measured in depression]
11.  ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
12.  HeartDisease: output class [1: heart disease, 0: Normal]

**Source**
This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The five datasets used for its curation are:

-   Cleveland: 303 observations
-   Hungarian: 294 observations
-   Switzerland: 123 observations
-   Long Beach VA: 200 observations
-   Stalog (Heart) Data Set: 270 observations

Total: 1190 observations  
Duplicated: 272 observations

`Final dataset: 918 observations`

Creators:
1.  Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
2.  University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
3.  University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
4.  V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

Donor to UC Irvine Machine Learning Repository:  
David W. Aha (aha '@' ics.uci.edu) (714) 856-8779

The datasets from the above sources were combined into the dataset I used by Kaggle user fedesoriano.

Data source Citation:
fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [May 22, 2023] from [https://www.kaggle.com/fedesoriano/heart-failure-prediction](https://www.kaggle.com/fedesoriano/heart-failure-prediction).


## Exploratory Data Analysis
Questions I Asked About the Data: 
1. How many positive and negative examples are there of the target variable?  
2. How are continuous variables distributed (in particular, are they normally distributed)?  
3. How do continuous variables change in conjunction with the target variable?  
4. How many examples are there of each categorical variable?  
5. How does each categorical variable change in conjunction with the target variable?

## Feature Selection With Inferential Statistics
### One-Way ANOVA
- p<0.05 for all features
- more about why I included it
### Chi-Squared Test
- p<0.05 for all features
- more about why I included it

## Classification Models
1. Logistic Regression
2. Random Forest
3. Support Vector Machine
4. Gaussian Naive Bayes
5. (Bernoulli Naive Bayes if I include it)
6. Neural Network

## Evaluation and Results
- sensitivity and specificity and Bayesian PDFs
- other metrics

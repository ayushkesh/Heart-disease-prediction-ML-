# Heart-Disease-Prediction
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![scikit-learnn](https://img.shields.io/badge/Library-Scikit_Learn-orange.svg)
1. [ Demo ](#demo)
2. [ Overview ](#overview)
3. [Description](#description)
4. [ Installation](#install)
4. [ Run ](#run)

<a name="demo"></a>
### Demo

* A glimpse of the __web app__:

- ![GIF](covid.gif)
#### Link of the deployed model _  https://heart-prediction-api.herokuapp.com/_

<a name="overview"></a>
### Overview
Health care field has a vast amount of data, for processing those data certain techniques are used.
Data mining is one of the techniques often used. Heart disease is the Leading cause of death worldwide.
This System predicts the arising possibilities of Heart Disease.
The outcomes of this system provide the chances of occurring heart disease.

#### Attribute Information
- Age
- Sex
- Chest pain type (4 values)
- Resting blood pressure
- Serum cholestoral in mg/dl
- Fasting blood sugar > 120 mg/dl
- Resting electrocardiographic results (values 0,1,2)
- Maximum heart rate achieved
- Exercise induced angina
- Oldpeak = ST depression induced by exercise relative to rest
- The slope of the peak exercise ST segment
- Number of major vessels (0-3) colored by flourosopy
- Thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

### Description
- Dataset is collected from kaggle.com 
- Data Cleaning, Data Visualization, EDA and model is built to predict Heart Disease
- Algorithms applied :
  * __KNeighborsClassifier__
  * __RandomForestClassifier__
- The model is successfully built and has achieved the highest accuracy of __99.02%__

### Installation
The Code is written in __Python 3.7.__ To install the required packages and libraries, run this command in the project directory after cloning the repository:

> pip install -r requirements.txt

<a name="run" > </a>
### Run

Create an environment and clone this repository. To run this project run a command into terminal :

> streamlit run app.py

• Please do ⭐ the repository, if it helped you in anyway.

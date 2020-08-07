# Capstone Project-Pump it Up! 
## Enhance the availability of clean water by predicting the functionality of water points in Tanzania

This Repository contains the final project that I conducted within the Data Science Coding Bootcamp neuefische in Hamburg. It is based on a data competition, held by [drivendata.org](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/), named Pump it up!

![](https://cdnuploads.aa.com.tr/uploads/Contents/2017/03/13/thumbs_b_c_919380a969cf7427774545cf4b641472.jpg?v=173523)


##  Content of this repository

The repository contains the following notebooks:

* **#1 Data Preprocessing**
This notebook contains all necessary steps to be conducted prior to the predictive modelling which includes:
  - Importation of the Dataset
  - Data Cleaning
  - Data Exploration and Visualisations
  - Feature Engineering

* **#2 Predictive Modelling**
This notebook contains the application of several supervised machine learning classification algorithms on the preprocessed Dataset. TheseThe are:
- Dummy Classifier
- Logistic Regression
- Decision Trees
- Random Forest
- AdaBoost
- XgBoost
The most promissing models were optimzed via Hyperparamter tuning applying a Randomized Grid Search. Further the minority class was oversampled by applying the Synthetic Minority Oversampling Technique (SMOTE) which further improved the results. 
 
* **README.md**
* **data**
Folder to store the relevant data.
* **figures**
Folder to store the figures produced within the project.
* **Pump_it_up.ppt**
A powerpoint presentation which contains the obtained results of the analysis

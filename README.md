# Flight Delay Prediction

## Project Overview

This project uses Machine Learning to predict whether a flight will be delayed based on historical flight data. The objective is to help airlines and airports identify potential delays and improve operational planning.

## Objectives

* Analyze flight data
* Clean and preprocess the dataset
* Encode categorical variables
* Train a Machine Learning model
* Predict flight delays
* Evaluate model performance

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## Dataset Summary

* Total Flights Analyzed: 49,387
* Features Used: 8
* Target Variable: DEP_DEL15 (Delayed or Not)

## Data Preprocessing

* Removed unnecessary columns
* Handled missing values
* Encoded categorical features into numerical values
* Prepared data for Machine Learning

## Machine Learning Model

* Algorithm: Random Forest Classifier
* Training Samples: 39,509
* Testing Samples: 9,878

## Model Performance

* Accuracy: 93.67%
* Correct Predictions: 9,253
* Wrong Predictions: 625

## Results

The Random Forest Classifier achieved an accuracy of 93.67%, demonstrating strong predictive performance on the flight delay dataset. The model can be used as a foundation for predicting delays and supporting airline decision-making.

## Future Scope

* Real-time flight delay prediction
* Weather data integration
* Airline performance analysis
* Airport congestion prediction
* Flight scheduling optimization

## Dataset

The dataset used in this project is not included in this repository because of its large file size (~75 MB).

To run this project:
1. Download the dataset.
2. Place the CSV file in the project folder.
3. Run the notebook.

The notebook expects the dataset file to be present in the same directory.

## Author

Naghul Aadhithya M

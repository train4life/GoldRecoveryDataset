# Project: Gold Recovery Prediction

Overview:
Welcome to the Gold Recovery Prediction project! In this repository, you will find the code and resources to predict gold recovery using the provided dataset. The project involves data preparation, analysis, and building a predictive model to achieve accurate gold recovery predictions.

Objective:
The main goal of this project is to build a model that accurately predicts gold recovery using the available data.

Instructions:

Step 1: Prepared the Data

1.1. Opened the files and looked into the data:

Files: gold_recovery_train.csv, gold_recovery_test.csv, gold_recovery_full.csv

1.2. Checked recovery calculation:

Calculated the recovery for the rougher.output.recovery feature in the training set.
Calculated the Mean Absolute Error (MAE) between your calculations and the feature values.
Provided your findings regarding the accuracy of the recovery calculation.

1.3. Analyzed features not available in the test set:

Identified parameters that are missing in the test set.
Determined the type of these parameters.

1.4. Performed data preprocessing:

Cleaned and preprocessed the data as needed.

Step 2: Analyzed the Data

2.1. Concentrations of metals:

Observed how the concentrations of gold (Au), silver (Ag), and lead (Pb) change at different purification stages.

2.2. Feed particle size distributions:

Compared the feed particle size distributions in the training and test sets.
Addressed any significant variations that could affect model evaluation.

2.3. Total concentrations of substances:

Examined total concentrations at different stages: raw feed, rougher concentrate, and final concentrate.
Identified and handled any abnormal values in the total distribution.

Step 3: Build the Model

3.1. Wrote a function for the final sMAPE value:

Implemented a function to calculate the symmetric Mean Absolute Percentage Error (sMAPE).

3.2. Train and evaluat models:

Trained various models using cross-validation.
Selected the best-performing model.
Tested the selected model using the test sample.
Provided findings based on model evaluation.

# Overview

The problem I am trying to solve is predicting whether flights will be cancelled or delayed. The target variable is the ground truth flight status of the flights in the dataset; this is a ordinal target variable with options: on time, slight delay, medium delay, large delay, and cancelled. Because the target variable is ordinal, this is a classification problem. 

# Environment and data

The required pip packages are listed in requirements.txt

Download the 2022 Combined flight data .parquet file from here (https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022) into the 'data' folder before running any code.

# Source code and saved models

The source code for the project can be found in the 'src' folder. It is all contained in one jupyter notebook file. The accompanying models from the training code can be found and loaded from the 'results' folder. The .save file for the KNN Classifier had to be omitted from the repository given its large size.

# Report and figures

The report for this project can be found in the 'report' folder and the accompanying figures can be found in the 'figures'



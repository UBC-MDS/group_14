# Rainfall Prediction in Australia

A group project for UBC MDS DSCI 525 - Web and Cloud Computing.

## Overview

This project involves working with big data. We will be building and deploying ensemble machine learning models in the cloud to predict daily rainfall in Australia on a large dataset (~6 GB), where features are outputs of different climate models, and the target is the actual rainfall observation.

In Milestone 1, we will explore different methods to load, save and transform large datasets whilst also demonstrating the limits of our personal computers. The Jupyter notebook can be found [here](https://github.com/UBC-MDS/rainfall-prediction-group14/blob/main/notebooks/Milestone_1.ipynb).

In Milestone 2, we transfer the data into the cloud and set up the infrastructure for machine learning. It involves setting up an EC2 instance in AWS, moving data in an S3 bucket, and data wrangling.
The Jupyter notebook can be found [here](https://github.com/UBC-MDS/rainfall-prediction-group14/blob/main/notebooks/Milestone_2.ipynb).

In Milestone 3, our team set ups an EMR cluster with Spark, Hadoop, JupyterEnterpriseGateway, JupyterHub 1.1.0, and Livy. We developed a Time Series Model using RandomForestRegressor to predict the daily rainfall in Sydney. We used spark's MLlib to optimize hyperparameters for the model. The Jupyter notebook can be found [here](https://github.com/UBC-MDS/rainfall-prediction-group14/blob/main/notebooks/Milestone3.ipynb).

In Milestone 4, an API is developed using flask, saving the app.py script in the EC2 instance followed by deploying the API in EC2 instance's public IPv4 address. The Jupyter notebook can be found [here](https://github.com/UBC-MDS/rainfall-prediction-group14/blob/main/notebooks/Milestone4.ipynb).

## Data

The complete daily rainfall dataset used for prediction can be found from [figshare](https://figshare.com/articles/dataset/Daily_rainfall_over_NSW_Australia/14096681)

## Contributing

| Member        | Github                                            |
|---------------|---------------------------------------------------|
| Mel Liow  | [mel-liow](https://github.com/mel-liow)   |
| Rohit | [rrrohit1](https://github.com/rrrohit1)  |
| Rowan Sivanandam    | [Rowansiv](https://github.com/Rowansiv)         |

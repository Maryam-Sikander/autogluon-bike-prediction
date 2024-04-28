# Predict Bike Sharing Demand with AutoGluon
![model_test_score.png](image/download.png)

## Overview
This project is part of **`AWS Machine Learning Engineer Nanodegree`**

This project focuses on using AWS open-source AutoML library, AutoGluon to predict the bike sharing demand using the Kaggle Bike Sharing demand dataset. The ultimate objective is to use AutoGluon's 'Tabular Prediction' to achieve accurate AutoML-based baseline models without dealing with a lot of cumbersome issues like data cleaning, feature engineering, hyperparameter optimization, model selection, etc.
Visit [Kaggle Bike Sharing Demand Competition](https://www.kaggle.com/c/bike-sharing-demand)
[Dataset](https://www.kaggle.com/c/bike-sharing-demand/data)
## Project specific files:
* Jupyter notebook with code run to completion [jupyter notebook](Bike_sharing_demand.ipynb)
* HTML export of the jupyter notebook [jupyter notebook](Bike_sharing_autogluon.html)
* Report detailing which methods provided the best score improvement and why. [Project Report](project_report.md)

## Getting Started
* Clone this template repository  `git clone git@github.com:udacity/nd009t-c1-intro-to-ml-project-starter.git` into AWS Sagemaker Studio (or local development).
* Visit the [Kaggle Bike Sharing Demand Competition](https://www.kaggle.com/c/bike-sharing-demand) page. Here are the overall details about the competition including overview, data, code, discussion, leaderboard, and rules. Primarily focus is on the data and ranking sections.

### Dependencies

```
Python 3.7
MXNet 1.8
Pandas >= 1.2.4
AutoGluon 0.2.0 
```

### Installation
For this project, We have to use Sagemaker Studio provided by AWS Workspace. This will simplify much of the installation needed to get started.
1. Notebook is using a `ml.t3.medium` instance (2 vCPU + 4 GiB)
2. Notebook is using kernel: `Python 3 (MXNet 1.8 Python 3.7 CPU Optimized)`

For local development, you will need to setup a jupyter lab instance.
* Follow the [jupyter install](https://jupyter.org/install.html) link for best practices to install and start a jupyter lab instance.
* If you have a python virtual environment already installed you can just `pip` install it.
```
pip install jupyterlab
```
* There are also docker containers containing jupyter lab from [Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html).

## Project Instructions

1. Create an account with Kaggle.
2. Download the Kaggle dataset using the Kaggle python library.
3. Train a model using AutoGluon’s Tabular Prediction and submit predictions to Kaggle for ranking.
4. Use Pandas to do some exploratory analysis and create a new feature, saving new versions of the train and test dataset.
5. Rerun the model and submit the new predictions for ranking.
6. Tune at least 3 different hyperparameters from AutoGluon and resubmit predictions to rank higher on Kaggle.
7. Write up a report on how improvements (or not) were made by either creating additional features or tuning hyperparameters and why you think one or the other is the best approach to invest more time in.

## License
[License](LICENSE.txt)

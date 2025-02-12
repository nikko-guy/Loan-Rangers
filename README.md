# Loan Rangers

## Nikko Gajowniczek, Conrad Barron, Oon Jie Rui

### Predicting Home Credit Default Risk
We are attempting to create a ML model that analyzes a Loan Applicant's available data to determine how likely they are to repay their debt responsibly. 
This problem is based on a past Kaggle competition, [found here.](https://www.kaggle.com/competitions/home-credit-default-risk/data)
We settled on solving this problem based on a number of factors and constraints.

We didn't want to do a classification problem, and were interested in doing either NLP or image analysis.
It turns out the majority of NLP/image problems are classification problems, but we happened to find a problem with a large dataset and continuous target value.
We are curious to see if we can apply modern, cutting edge ML techniques to an older problem released 6 years ago. 

This model will be able to combine various unrelated features and synthesize a valuable risk analysis.
The output of the model will be a float between 0 and 1, a continuous problem.
The dataset provided has a vast quantity of features to examine/analyze. We will most likely simplify the problem space initially, and expand if possible.
Standard application data is provided; Applicant background, credit history, payment history.
Our Training dataset contains 300k entries labeled with a target score, which we will split into training and validation.

Initially, we plan on training our model with basic applicant background. We expect this to be useful for obvious rejections. Beyond that, it will be important to analyze historical data of the applicant for better results.

## Notebooks

- [tranche1_lgbm.ipynb](./tranche1_lgbm.ipynb): LGBM experiments and model training.
- [NeuralNet.ipynb](./NeuralNet.ipynb): Exploration of neural network models.
- [final_features.ipynb](./final_features.ipynb): Final feature engineering and model evaluation.
- [featureEngineering.ipynb](./featureEngineering.ipynb): Creation and exploration of feature relationships.
- [Bayesian Hyperparameter Search.ipynb](./Bayesian%20Hyperparameter%20Search.ipynb): Hyperparameter tuning using Bayesian optimization.

## Slides & Report

- [Project Milestone 1.md](./Project%20Milestone%201.md): Overview of project milestones and progress.
- [Milestone 4.pdf](./Milestone%204.pdf): Detailed report and slides covering key findings.


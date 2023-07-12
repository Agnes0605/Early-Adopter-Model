# Early-Adopter-Model
Repository for Capstone Project at NetApp

**Data** Folder includes
- Datasets that NetApp gave us.
- company_with_score.csv is the scores of being early adopters.
- catboost_params.csv is the result of catboost model params.

**Rollup** Folder includes
- Notebooks of various methods of rolling up methods.

**Analyses.ipynb** is the notebook of EDA and how we distinguished early adopters. 

**Model** Folder includes
- early_adopter_catboost_firmographic is the catboost model of predicting early adopters; the input includes the feature from firmographic dataset.
- catboost.ipynb is the notebook of building CatBoost model.
- catboost_params.csv is the best parameters from grid search.

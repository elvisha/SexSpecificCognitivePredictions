# SexSpecificCognitivePredictions

This repository contains the Jupyter Notebook based implementation of the work described in: 
Dhamala, E., Jamison, K. W., Jaywant, A., & Kuceyeski, A. (2021). Shared functional connections within and between cortical networks predict individual cognitive abilities in males and females. bioRxiv: https://www.biorxiv.org/content/10.1101/2021.02.17.431670v2

Keywords: neuroimaging, connectomics, machine learning, functional connectivity, structural connectivity, crystallised cognition, fluid cognition, cognition, prediction

This implementation uses functional connectivity data to predict cognitive scores using sex-independent and sex-specific prediction models.


Description of files:

01_sexindependent_and_sexspecific_predictions.ipynb - Jupyter Notebook to optimise and run sex-independent and sex-specific models

02_generate_empirical_nulls.ipynb - Jupyter Notebook to generate empirical null models

03_evaluate_model_performance.ipynb - Jupyter Notebook to evaluate whether models are significantly better than the null models, and to evaluate whether are significantly different from one another in their prediction accuracy

04_feature_importance_reconstruction.ipynb - Jupyter Notebook to compute the reconstructed activation (feature importance) from the raw feature weights

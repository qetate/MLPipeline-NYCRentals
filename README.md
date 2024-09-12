# ML Pipeline for Short-Term Rental Prices in NYC

## Overview
This project involves building an end-to-end machine learning pipeline to estimate short-term rental prices in NYC. The goal is to develop a pipeline that predicts rental prices based on data of similar properties. The project uses automated ML pipelines to efficiently retrain and deploy the model.

## Technologies Used
- **Python#**: The programming language for building the pipeline and model.
- **Conda**: For managing project environments and dependencies.
- **MLflow**: For tracking experiments, managing the pipeline, and versioning models.
- **Hydra**: To manage configuration settings for different pipeline components.
- **Weights & Biases (W&B)**: To log experiments, monitor model performance, and maintain a model registry.
- **Scikit-learn**: For implementing machine learning algorithms and data preprocessing.

## Skills Demonstrated
- **Pipeline Automation**: Built a modular, reusable ML pipeline for automated data processing and model retraining using MLflow.
- **Hyperparameter Tuning**: Used techniques such as grid search to optimize model hyperparameters for better performance.
- **Experiment Tracking**: Used Weights & Biases and MLflow to track experiments, version models, and manage configurations efficiently.
- **Model Evaluation**: Evaluated model performance using metrics like RMSE, leveraging tools like Weights & Biases for tracking and visualization.
- **Model Deployment**: Deployed the trained model artifacts and prepared the pipeline for regular updates as new data becomes available.
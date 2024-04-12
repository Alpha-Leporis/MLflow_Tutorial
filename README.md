# MLflow_Tutorial

MLflow concepts:
• ML Experiment: It is the process of building Machine Learning Model.
• Experiment Run: An execution of code or single trial in an ML Experiment.
• Run Artifact : Output file associated in each stage of ML Run.
• Metadata : Experiment Information like Parameters, Start and End time etc.


What is Experiment Tracking?
Experiment tracking is the process of keeping track of all the relevant information from an ML
experiment, which includes:
•Source code
•Environment
•Data
•Model
• Hyperparameters
•Metrics

Why is Experiment tracking is so important?
It has basically three reasons:
• Reproducibility
• Organization
• Optimization

Tools used for Experiment Tracking:
• Mlflow
• Tensorboard
• ClearML
• Kubeflow
• Guild.ai
• DVC

Installing mlflow:
`$ conda create --name mlflow_env`
`$ conda activate mlflow_env`
`$ pip install mlflow`

To store all our metadata:
`$ mlflow ui --backend-store-uri sqlite:///mlflow.db`

To run jupyter lab:
`$ jupyter lab`

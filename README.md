# Neural Network Analysis - Customer Churn Prediction

## Objective
Build and analyze a feed-forward neural network model to predict customer churn.

## Dataset
Customer churn dataset with categorical and numerical features.

Target variable:
- churn
  - 1 = Customer churned
  - 0 = Customer retained

## Tasks Completed
- Dataset understanding
- Data preprocessing
- Neural network model building
- Model training and evaluation
- Hyperparameter experimentation

## Model Details
Baseline Model:
- Hidden Layers: 2
- Neurons: 16, 8
- Activation: ReLU
- Output Activation: Sigmoid
- Loss Function: Binary Crossentropy
- Optimizer: Adam

## Results
The model achieved high accuracy due to class imbalance, but confusion matrix showed weak churn detection.

## Files
- notebook.ipynb
- requirements.txt
- results/model_comparison_table.csv
- results/evaluation_outputs.png

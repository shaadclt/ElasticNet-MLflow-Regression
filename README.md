# MLflow ElasticNet Regression

This repository contains code for training an ElasticNet regression model using MLflow. The model predicts the quality of wine based on various features.

## Requirements

- Python (>=3.6)
- MLflow (>=1.20.0)
- pandas
- numpy
- scikit-learn

## Dataset

The dataset used for training the model is `wine-quality.csv`, which contains various features of wine samples along with their quality ratings.


## Project Structure


- `wine-quality.csv`: Dataset file.
- `elasticnet_regression.py`: Python script for training the ElasticNet regression model.
- `README.md`: This file.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/shaadclt/ElasticNet-MLflow-Regression.git
```

2. Navigate to the project directory:

```bash
cd ElasticNet-MLflow-Regression
```

3. Run the training script with desired alpha and l1_ratio values:

```bash
python train.py <alpha> <l1_ratio>
```
Replace **'alpha'** and **<l1_ratio>** with the desired values for the ElasticNet hyperparameters. if not provided, default values (alpha=0.5, l1_ratio = 0.5) will be used.


# Results

After running the training script, MLflow will log the model parameters, metrics and the trained model itself. You can view the results in the MLflow UI.
```bash
mlflow ui
```

# License
This project is licensed under the MIT License.

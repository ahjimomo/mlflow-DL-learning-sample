# MLflow ANN Deep Learning Project

This project explores training and tracking an Artificial Neural Network (ANN) using MLflow for experiment management.

We will be using the [white wine quality dataset on GitHub](https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/whitewines.csv) for this exercise. 

## Overview

The goal of this project is to:
- Run a hyperparameter sweep for fine-tuning
- Track experiments, parameters, metrics, and artifacts using MLflow
- Choose the best run to register in MLflow model registry
- Deploy model to a REST API
- Building a container image suitable for deployment to a cloud platform
- Demonstrate a clean local MLOps workflow on macOS

## Project Structure

```text
mlflow_ann_dl/
├── requirements.in     # Top-level dependencies
├── rdl_ann.ipynb       # Script to build & log model
├── inference.ipynb     # Script to load registered model (Future)
├── Data/
|   └── test.csv        # Data hidden from model for testing
├── requirements.txt    # Locked dependencies
├── README.md
└── .gitignore
```

## Prerequisites

- Python 3.10 / Python 3.9
- macOS (Apple Silicon recommended)
- Git

## Setup

Create, activate a virtual environment:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

Upgrading setup tools wheels and installing required dependencies:
```bash
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```

##  Run Projects

This project uses Jupyter Notebook for ease of reading.

Opening MLFlow Tracking UI:
```bash
mlflow ui
```

## Future Improvements
- To enable inferencing of the best model and to use it as practice
    - notebook to be named `inference.ipynb`
    - Test data saved in file `./data/test.csv` for usage
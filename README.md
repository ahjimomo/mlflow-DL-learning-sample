# MLflow ANN Deep Learning Project

This project explores training and tracking an Artificial Neural Network (ANN) using MLflow for experiment management.

## Overview

The goal of this project is to:
- Train ANN models for regression/classification
- Track experiments, parameters, metrics, and artifacts using MLflow
- Demonstrate a clean local MLOps workflow on macOS

## Project Structure

```text
mlflow_ann_dl/
├── requirements.in     # Top-level dependencies
├── requirements.txt    # Locked dependencies
├── README.md
└── .gitignore
```

## Prerequisites

- Python 3.1
- macOS (Apple Silicon recommended)
- Git

## Setup

Create, activate a virtual environment:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

Installing required dependencies:
```bash
pip install -r requirements.txt
```

##  Running Projects

This project uses Jupyter Notebook for ease of reading.

Opening MLFlow Tracking UI:
```bash
mlflow ui
```

## Future Improvements



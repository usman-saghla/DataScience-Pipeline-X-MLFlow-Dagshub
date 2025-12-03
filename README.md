# DataScience Pipeline X (MLFlow + Dagshub)

A modular, end-to-end machine learning pipeline designed for seamless data handling, model training, and collaboration.

## Overview

This repository provides a simple yet powerful framework for managing machine learning projects. It covers all stages of the ML lifecycle, including data ingestion, validation, transformation, training, and evaluation. The pipeline integrates with **MLflow** for experiment tracking and **Dagshub** for version control and collaboration.

### Key Features:
- **Data Ingestion**: Efficiently load and manage data from various sources.
- **Data Validation**: Ensure data quality through comprehensive checks.
- **Data Transformation**: Includes feature engineering and preprocessing steps.
- **Model Training**: Automates the process of training models.
- **Model Evaluation**: Track and evaluate model performance with MLflow and Dagshub.

## ML Pipeline Workflow

1. **Data Ingestion**: Collect and load the necessary data.
2. **Data Validation**: Validate the integrity and consistency of the data.
3. **Data Transformation**: Perform feature engineering and preprocessing to prepare the data.
4. **Model Training**: Train your machine learning models with specified algorithms.
5. **Model Evaluation**: Evaluate the trained models using metrics and track them with MLflow, while also enabling collaboration via Dagshub.

## Setup and Configuration

1. **Update `config.yaml`**: Configure global settings and pipeline parameters.
2. **Update `schema.yaml`**: Define the structure and types of your data.
3. **Update `params.yaml`**: Set specific model and training parameters.
4. **Define New Entities**: Add or modify the entities used in the pipeline.
5. **Update Configuration Manager**: Adjust configurations in `src/config` to reflect changes.
6. **Update Pipeline Components**: Modify or add new components to the pipeline as necessary.
7. **Update the Pipeline**: Ensure the pipeline reflects the updated components and configurations.
8. **Modify `main.py`**: Adjust the main script to run the pipeline and reflect all changes.

## Getting Started

Clone this repository and set up your environment:

```bash
git clone <repo-url>
cd <repo-directory>
# Install required dependencies
pip install -r requirements.txt

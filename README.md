# Loan Eligibility Prediction using XGBoost on SageMaker

This is a sample end-to-end machine learning project designed to help understand how **Amazon SageMaker** and **Amazon S3** work together in a typical ML workflow. It walks through the complete process of preparing data, training a model using SageMaker’s built-in XGBoost algorithm, deploying the model as a real-time endpoint, and testing predictions via a local Jupyter notebook. While the focus is on demonstrating the pipeline and integration with AWS services, the model’s performance can be significantly improved with better **feature engineering** and **hyperparameter tuning**. This project serves as a foundational exercise for learning ML deployment in cloud environments.



## 📌 Overview

This project demonstrates building, training, deploying, and testing a machine learning model to predict loan eligibility using Amazon SageMaker and XGBoost. The solution includes:

- Preprocessing and uploading data to S3
- Training a model on SageMaker using built-in XGBoost
- Deploying the model as a SageMaker endpoint
- Testing the endpoint using a local Jupyter notebook

## ⚙️ Requirements

To run this project successfully, you need:

- ✅ An AWS Account with permissions for:
  - SageMaker
  - S3 (read/write access)
- ✅ Python 3.8 or above
- ✅ Jupyter Notebook
- ✅ The following Python packages:
  - `boto3`
  - `sagemaker`
  - `pandas`
  - `scikit-learn`


### 📸 Screenshots

#### 🔹 1. S3 Bucket – Folder Structure
<img width="947" height="400" alt="Screenshot 2025-07-17 204121" src="https://github.com/user-attachments/assets/bd29772e-3e12-45ca-9aea-b8ebc9375776" />


#### 🔹 2. S3 Output Folder – Trained Model Artifacts
<img width="950" height="422" alt="Screenshot 2025-07-17 204153" src="https://github.com/user-attachments/assets/c97d14af-8b15-44d2-8639-f9e8d4632029" />









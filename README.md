# Machine Learning Pipeline: Persona Mapping

## 🤖 Overview
A machine learning pipeline built on Azure ML Studio to classify customer personas using XGBoost and Naive Bayes. The models predict user segments for targeted marketing based on behavioral and demographic data.

## 🛠️ Technologies
- Azure ML Studio
- Python (scikit-learn, XGBoost)
- Azure Data Factory
- Pandas, NumPy

## 🧠 Features
- Data ingestion and preprocessing
- Two classification models: Naive Bayes & XGBoost
- Evaluation metrics: Accuracy, Precision, Recall
- Pipeline scheduling with ADF

## 🖼️ Pipeline Diagram
![Pipeline Diagram](azureml_pipeline_diagram.png)

## 📊 Dataset
- `persona_dataset.csv`: Includes user_id, activity level, location, purchase history, etc.

## 🧪 Results
- XGBoost Accuracy: 85%
- Naive Bayes Accuracy: 78%

## ⚙️ Setup
Run notebooks in Azure ML Studio or locally with Jupyter Notebook. Use ADF for scheduling and automation.


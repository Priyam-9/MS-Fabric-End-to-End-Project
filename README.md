# MS-Fabric-End-to-End-Project

## Overview
This project focuses on predicting the likelihood of a patient having a stroke based on lifestyle, work type, and medical history using Microsoft Fabric.

The project demonstrates an end-to-end data pipeline including:

- Data Ingestion
- Data Transformation
- Data Engineering
- Data Visualization
- Machine Learning Model Development

The solution was built using Microsoft Fabric workloads including:

- Data Engineering (Data Factory & Synapse Engineering)
- Data Science
- Data Analytics (Power BI)

---

# Project Architecture

The project follows a modern Microsoft Fabric architecture workflow:

1. Raw stroke prediction dataset is ingested into Microsoft Fabric.
2. Data transformation and cleaning are performed using Dataflow Gen2.
3. The cleaned dataset is loaded into a Lakehouse.
4. Data Factory pipelines orchestrate the ingestion process.
5. SQL endpoints are used to create fact and dimension views.
6. Power BI is connected for visualization and reporting.
7. A Machine Learning model (Support Vector Machine) is trained using Spark notebooks.

---

# Technologies Used

- Microsoft Fabric
- Dataflow Gen2
- Data Factory
- Lakehouse
- SQL Endpoint
- Power BI
- Spark Notebook
- Python
- Support Vector Machine (SVM)

---

# Data Engineering

The dataset was extracted, transformed, and loaded into a Fabric Lakehouse using Dataflow Gen2.

Power Query Online was used for transformation and preprocessing before publishing the dataflow.

The published dataflow was orchestrated using Data Factory pipelines to automate ingestion into the Lakehouse.

The Lakehouse stores data in Delta format and provides SQL endpoints for querying and analytical modeling.

SQL views were created for:
- Fact Tables
- Dimension Tables

These views were later used for reporting and analytics.

---

# Exploratory Data Analysis & Visualization

A semantic data model was created using the SQL views generated from the Lakehouse.

DAX measures were implemented to support analytical reporting and KPI calculations.

Power BI was used to create:
- Revenue dashboards
- Trend analysis
- Stroke risk insights
- Interactive visualizations

The project also explores integration between:
- Microsoft Fabric
- Power BI Desktop
- SQL Endpoint connectivity

---

# Machine Learning Model

A Support Vector Machine (SVM) model was developed using Spark Notebooks within Microsoft Fabric.

The notebook was connected directly to the Lakehouse for model training and evaluation.

## ML Workflow

- Data preprocessing
- Feature engineering
- Model training
- Prediction
- Accuracy evaluation

## Model Accuracy

The model achieved approximately:

```text
95% Accuracy
Dataset

Stroke Prediction Dataset from Kaggle:

https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

Key Learnings

This project provided hands-on experience with:

End-to-end Microsoft Fabric implementation
Data orchestration pipelines
Lakehouse architecture
SQL-based analytical modeling
Power BI reporting
Machine Learning integration inside Fabric
Author
Priyam Patel

Aspiring Data Analyst & Machine Learning Engineer

Focused on:

Microsoft Fabric
Power BI
Data Engineering
Machine Learning
Analytics Engineering

GitHub:
https://github.com/Priyam-9 
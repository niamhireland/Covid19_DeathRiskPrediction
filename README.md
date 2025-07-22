# COVID-19 Death Risk Prediction

![CDC Logo](images/CDC_logo.svg)

## 📘 About The Project

This project was completed when I studied Data Analytics during my MSc. The objective was to build a data model to understand and predict death risk associated with COVID-19, using real-world case surveillance data collected by the CDC.

The task was divided into two main stages, with one notebook corresponding to each:

### 🔍 Data Understanding & Preparation
I was provided with anonymised patient records containing demographic, clinical, and outcome information. From this, I:
+ 📊 Produced a **data quality report**
+ 🧹 Outlined a **systematic data cleaning** and transformation plan
+ 🧠 Performed **exploratory feature analysis**
+ 🧩 Created **domain-informed features** for predictive modelling

### 🤖 Model Training & Evaluation
Using the cleaned dataset, I trained multiple models to identify high-risk cases:

+ 🧪  Trained **Logistic Regression**, **Linear Regression**, and **Random Forest** models
+ 📏 Evaluated each using **precision**, **accuracy**, and **F1 score**
+ 🔍 Identified strengths and weaknesses of each model's performance.
+ 💡 Recommended future improvements and additional features

## 📁 Repository Structure

```bash
Covid19_DeathRiskPrediction/
│
├── data/                         # All CSVs used in the project.
│   ├── raw                       # The inital CSV file provided to me.
│   └── cleaned_data              # The product of the initial data cleaning.
│   └── test_train_data           # 30% of the cleaned dataset, reserved for testing against models 
│
├── notebooks/                    # Analysis steps (conducted in Jupyter Notebook)
│   ├── Homework1.ipynb           # Details the data cleaning and processing. 
│   ├── Homework2.ipynb           # Training, testing and evaluating various models on the dataset.
│
├── reports/             
│   ├── data_quality_report.pdf    # Details the quality issues in the original dataset.
│   └── data_quality_plan.pdf      # Outlines steps that will be taken to rectify the above. 
```

## 🗃️ Dataset

Data sourced from the [CDC COVID-19 Case Surveillance Public Use Dataset](https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data-with-Ge/n8mc-b4w4). 

Each student worked with a unique, anonymised subset. The specific subsection of data I worked with was selected by my lecturer and is available in this repo, at data/raw . 

My dataset contains 50,000 records and includes both survivors and non-survivors.

## 🛠️ Built With 

- 🐍 `Python`
- 📊 `pandas`, `numpy` – Data manipulation
- 📉 `matplotlib`, `seaborn` – Visualization
- 🧠 `scikit-learn` – Feature engineering and modeling
- 📓 `Jupyter notebook` – development and presentation

## 🙏 Thanks To

My lecturer Georgiana Ifrim, who taught the Data Analytics module of the MSc Computer Science in UCD. Her guidance and support was invaluable.

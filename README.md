# CSCI 164 Final Project
This repository contains the final project for Applied Machine Learning using the scikit-learn library. The project focuses on building, evaluating, and comparing multiple supervised learning models across different real-world datasets. The goal is to demonstrate a complete machine learning workflow, including data preprocessing, model training, hyperparameter tuning, evaluation, and comparison.


## Authors
Laura Mas Serra

Kazi Islam

Manuel Domingo Mora


## Datasets Used
This project uses the following datasets:
- [Phishing Detection](https://www.kaggle.com/datasets/eswarchandt/phishing-website-detector)
- [Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- [Weather Forecast](https://www.kaggle.com/datasets/zeeshier/weather-forecast-dataset)

\* Each dataset was selected to represent different classification challenges, including imbalanced classes, mixed feature types, and real-world noise.


## Machine Learning Models
The following models were implemented using scikit-learn:
- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
  
\* Each model was evaluated and compared across datasets using consistent preprocessing and evaluation methods.


## Methodology
The project follows a standard machine learning pipeline:
- Data exploration and understanding
- Data preprocessing (encoding, scaling, handling missing values)
- Train-test split
- Model training
- Hyperparameter tuning using GridSearchCV
- Model evaluation using multiple metrics (Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrices)
- Multiple graphs employed to display results and analysis


## Repository Structure
```text
├── notebooks/
│   ├── BankMarketing.ipynb
│   ├── phishing.ipynb
│   ├── csci164_project_weather.ipynb
│   ├── bankMarketing_dataset.csv
│   ├── phishing_dataset.csv
│
├── report/
│   ├── final_report.pdf
│
├── README.md
```
## Results Summary
Three models were evaluated across all datasets: Logistic Regression, Decision Tree, and K-Nearest Neighbors (KNN). Overall, the Decision Tree model consistently performed best, particularly in capturing non-linear relationships and handling class imbalance. It achieved the highest accuracy across all datasets, including near-perfect performance in the weather dataset and strong results in both phishing and telemarketing tasks. Logistic Regression served as a stable baseline but struggled with complex patterns and minority class detection, while KNN performed well on cleaner datasets but was less effective on imbalanced data.

## Notes
The notebooks include all the code and outputs along with text explanation.
The Final Report discusses the entire Methodology in depth, analyzes the results obtained along with graphs and figures, and compares our work with prior published work.

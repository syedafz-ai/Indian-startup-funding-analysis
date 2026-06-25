# Indian Startup Funding Analysis

Data Mining Tools Lab Mini Project — CSD 2258
B.S. Abdur Rahman Crescent Institute of Science and Technology

## Overview
Analysis of the Indian Startup Funding ecosystem (2020–2025) using data mining and machine learning techniques in R.

## Objectives
- Predict startup funding stage (Early vs Late) using classification models
- Segment startups by funding behavior using clustering
- Discover industry-city funding patterns using association rule mining

## Dataset
- Source: Kaggle — Indian Startup Funding Dataset (2020–2025)
- Features: Startup Name, Industry, City, Investors, Investment Type, Investment Amount, Date

## Models Used

| Model | Accuracy | Precision | Recall | F1 |
|---|---|---|---|---|
| Logistic Regression | 81.73% | 75% | 90% | 81.82% |
| Decision Tree | 84.01% | 78.26% | 90% | 83.72% |
| Random Forest | 81.27% | 78.09% | 82% | 80% |

## Techniques Applied
- Data Preprocessing (missing value handling, encoding, scaling)
- Classification: Logistic Regression, Decision Tree, Random Forest
- Clustering: K-Means (Elbow Method for optimal K)
- Association Rule Mining: Apriori algorithm
- Visualization: ggplot2

## Key Findings
- Decision Tree achieved highest accuracy (84.01%)
- Investment Amount was the most influential feature
- EdTech, FinTech, and HealthTech were the most funded industries
- Bengaluru, Mumbai, and Delhi are the top startup hubs
- K-Means segmented startups into 3 funding levels: Low, Mid, High

## Tools
R 4.5.2 · caret · randomForest · arules · ggplot2 · factoextra

## Report
Full project report with visualizations available above as PDF.

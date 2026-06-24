## MACHINE LEARNING PORTFOLIO

This repository contains machine learning projects focused on data preparation, feature engineering, exploratory data analysis, predictive modeling, model evaluation, and business insights. The projects demonstrate regression and classification workflows using real-world datasets from retail analytics and sports analytics domains.

## 📌 Project Highlights

| Project | Domain | Problem Type | Dataset Size | Key Output |
|---|---|---|---:|---|
| [Retail Sales Forecasting](retail-sales-forecasting) | Retail Analytics | Regression | 9,994 rows x 20 columns | Sales and profit analysis with Linear Regression and XGBoost models |
| [NBA Player Performance Prediction](nba-player-performance-prediction) | Sports Analytics | Classification | 645,953 rows x 29 columns | Player impact classification using Logistic Regression and K-Nearest Neighbors |

## 📊 Dataset Sources

| Project | Dataset | Source | Key Features |
|---|---|---|---|
| Retail Sales Forecasting | Superstore Dataset | [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) | Order details, customer segments, geography, product categories, shipping modes, sales, discount, profit |
| NBA Player Performance Prediction | NBA Analysis Dataset | [Kaggle](https://www.kaggle.com/datasets/chandra03/nba-analysis) | Player details, team information, season records, minutes played, scoring metrics, rebounds, assists, steals, blocks, plus-minus |

Datasets are not included in this repository due to file size and source management considerations. To run the notebooks locally, download the datasets from Kaggle and place them inside the respective `data` folders using the filenames mentioned above.

## 📂 Repository Structure

```text
machine-learning/
├── README.md
├── requirements.txt
├── .gitignore
├── retail-sales-forecasting/
│   ├── retail_sales_forecasting.ipynb
│   ├── data/
│   │   └── README.md
│   └── documents/
│       └── retail_sales_forecasting_report.pdf
└── nba-player-performance-prediction/
    ├── nba_player_performance_prediction.ipynb
    └── data/
        └── README.md
```

## 🧩 Skills Demonstrated

- Data preparation and cleaning
- Exploratory data analysis
- Feature engineering
- Regression modeling
- Classification modeling
- Model training and testing
- Hyperparameter tuning
- Model evaluation using accuracy, R², RMSE, and classification metrics
- Data visualization for model interpretation
- Business and analytical insight generation
- Jupyter Notebook project documentation

## 💻 Technology Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Pickle

## 📚 Project Summaries

### Retail Sales Forecasting

This project analyzes retail transaction data to understand revenue and profit drivers across customer segments, cities, states, product categories, and shipping modes. The workflow includes data preparation, feature engineering, label encoding, outlier handling, exploratory analysis, regression modeling, and model evaluation.

Linear Regression and XGBoost models were trained and evaluated, with XGBoost achieving approximately 65% R² after tuning. The analysis identified discount as one of the strongest factors affecting profitability, providing practical insight into pricing, shipping, and customer segmentation decisions.

### NBA Player Performance Prediction

This project analyzes NBA player performance records to classify player impact using machine learning. The workflow includes data cleaning, missing-value handling, datatype correction, feature selection, target-variable engineering, exploratory analysis, model training, and model evaluation.

The project creates a modified plus-minus based target variable to represent player impact and uses performance metrics such as minutes played, points, rebounds, assists, steals, blocks, and shooting-related statistics for prediction. Exploratory analysis was used to understand team-level and player-level performance patterns before modeling.

A Logistic Regression model achieved approximately 62% accuracy and outperformed a K-Nearest Neighbors model, which achieved approximately 56% accuracy. The models were evaluated using accuracy score, confusion matrix, and classification report. The project also includes a career statistics to aggregate player performance across seasons.

## ▶️ Running the Notebooks

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Download the datasets from the Kaggle links listed above and place them in the correct project `data` folders:

```text
retail-sales-forecasting/data/superstore.csv
nba-player-performance-prediction/data/nba.csv
```

Open any project notebook using Jupyter Notebook or VS Code:

```bash
jupyter notebook
```

## 🚀 Purpose

The purpose of this repository is to present practical machine learning projects in a clean, structured, and well-documented format. These projects demonstrate how real-world datasets can be prepared, explored, modeled, evaluated, and converted into meaningful analytical and business insights.

# ML
PROJECTS
This project implements a Machine Learning classification model using a Random Forest algorithm to predict customer categories based on purchase behavior. It includes end-to-end steps such as data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

ML-Customer-Classification/
│
├── data/
│   ├── raw/                  # Original dataset
│   └── processed/            # Cleaned dataset
│
├── notebooks/
│   └── eda.ipynb             # Data analysis & visualization
│
├── src/
│   ├── preprocessing.py      # Data cleaning & encoding
│   ├── train.py              # Model training
│   ├── evaluate.py           # Model evaluation
│   └── utils.py              # Helper functions
│
├── models/
│   └── random_forest.pkl     # Saved trained model
│
├── outputs/
│   ├── plots/                # Graphs & visualizations
│   └── reports/              # Results / metrics
│
├── requirements.txt          # Dependencies
├── README.md                 # Project documentation
└── .gitignore

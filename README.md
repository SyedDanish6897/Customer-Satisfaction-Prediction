**Customer Satisfaction Prediction with Charts**

This project predicts customer satisfaction ratings using XGBoost and visualizes insights with charts for easy analysis. It’s designed to generate high-quality plots for reporting or presentation purposes.

Table of Contents

Overview

Features

Dataset

Installation

Usage

Output

Dependencies

**Overview**

Customer support teams often need insights into customer satisfaction ratings to improve services. This project:

Loads and preprocesses the dataset.

Balances the target class using SMOTE.

Trains an XGBoost classifier.

Generates various charts for analysis and PPT/report use.

The code is structured for clarity, speed, and ease of understanding.

**Features**

Handles categorical and numerical features with preprocessing pipelines.

Balances class distribution using SMOTE.

Trains XGBoost classifier with configurable hyperparameters.

Generates and saves charts:

Confusion matrix

Classification report heatmap

Customer satisfaction distribution

Pie chart for satisfaction split

Average satisfaction by categorical features

Boxplots for numeric features vs satisfaction

Charts are saved in outputs/ folder, ready for PPT or reports.

**Dataset**

The dataset should be in CSV format.

Expected target column: Customer Satisfaction Rating.

Ensure the path is correct in the code:

**DATA_PATH = "../data/customer_support_tickets.csv"**


Note: Modify the path if your dataset is stored elsewhere.

**Installation**

Clone the repository:

git clone https://github.com/SyedDanish6897/customer-satisfaction-prediction.git
cd customer-satisfaction-prediction


Install required Python packages:

**pip install -r requirements.txt**


Optional: Use a virtual environment for better isolation:

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows


**Output:**

Model evaluation metrics printed in console.

Charts saved in outputs/ folder for reporting or PPT use.

Outputs

confusion_matrix.png – Confusion matrix heatmap

classification_report.png – Classification report heatmap

satisfaction_distribution.png – Customer satisfaction count plot

satisfaction_pie.png – Pie chart of customer satisfaction

satisfaction_by_<feature>.png – Average satisfaction by categorical features

<feature>_vs_satisfaction.png – Boxplots of numeric features vs satisfaction


**Dependencies**

Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

xgboost

imbalanced-learn

**Install all dependencies using:**

pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn

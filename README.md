🌍 Global Emissions Data Analysis
📌 Overview

This project explores global CO₂ and greenhouse gas emissions using data visualization, time series analysis, and dimensionality reduction techniques.

The objective is to analyze emission patterns across countries and continents, examine relationships between economic indicators and emissions, and identify structural differences using Principal Component Analysis (PCA).

📊 Project Components
1️⃣ Data Cleaning

Handled missing values using time-series interpolation

Addressed mild outliers

Exported cleaned dataset for reproducibility

2️⃣ Visualizing Amounts

Top 10 emitting countries (2020)

Stacked bar charts comparing CO₂, Methane, and Nitrous emissions

3️⃣ Visualizing Associations

GDP vs CO₂ scatter plots (colored by continent)

Bubble charts with population scaling

Correlation matrix (CO₂, GDP, Methane, Nitrous)

4️⃣ Visualizing Proportions

Emission share by continent

Comparative regional breakdowns

5️⃣ Time Series Analysis

CO₂ emissions from 2000–2024

5-year moving average smoothing

Trend interpretation across major emitters

6️⃣ PCA Representation

Standardized continent-level features

Reduced 5 variables to 2 principal components

Explained variance analysis

2D visualization of continent clusters

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn (PCA)

📈 Key Insights

Emissions are concentrated among a subset of high-output economies.

Economic output does not uniformly predict emissions across regions.

PCA reveals structural differences between continents in emission and economic profiles.

Time series trends show long-term shifts rather than short-term volatility.

📁 Repository Structure
analysis.ipynb
cleaned_data.csv
README.md
requirements.txt

🚀 How to Run

Clone the repository

Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook analysis.ipynb

📌 Author

Kunal Gandhi
Data Analytics | Visualization | Machine Learning

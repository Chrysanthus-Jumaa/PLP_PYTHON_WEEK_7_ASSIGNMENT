### 🚗 PLP Python Week 7 Assignment
📌 Project Overview
This project explores a dataset of used vehicles with the goal of uncovering patterns and relationships between various features such as price, mileage, accident history, and brand popularity. The dataset is large and rich, offering opportunities for data cleaning, imputation, visualization, and hypothesis testing.

🔧 Key Steps Performed
Data Cleaning: Identified and handled missing values, especially in the accident_history column.

Imputation: Replaced null values in accident_history with random selections from valid categories (None, Minor, Major) to preserve data volume.

Exploratory Data Analysis:

Scatterplot of price vs. mileage to test the hypothesis: lower mileage leads to higher price.

Bar chart of brand_popularity against make to visualize brand strength.

Histogram to examine the distribution of price, revealing a right-skewed pattern.

Insights: Observed trends and distributions that could inform pricing strategies or vehicle valuation models.

📁 Dataset
Due to its size, the dataset is not included in this repository. You can access it via the following link:

Download Dataset Here https://www.kaggle.com/datasets/metawave/vehicle-price-prediction

📊 Tools Used
Python

Pandas

NumPy

Matplotlib

Seaborn

🧠 Hypothesis Tested
Lower mileage correlates with higher vehicle price.

This was visualized using a scatterplot and supported by observable trends in the data.

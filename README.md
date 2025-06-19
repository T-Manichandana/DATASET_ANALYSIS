# DATASET_ANALYSIS
# Description
🧵 True Cost of Fast Fashion - Data Analysis & Prediction
This repository contains an in-depth data analysis project focused on evaluating the true cost of fast fashion—a sector increasingly under scrutiny for its environmental and ethical impacts. The project explores relationships between sustainability indicators and fashion brand metrics using exploratory data analysis and machine learning.

📌 Project Details
Student Name: Mani Chandana

Roll No: 160623747089

Section: AI&DS - B

Dataset: true_cost_fast_fashion.csv

🎯 Objective
To uncover patterns and relationships in the dataset that highlight how brand practices (like carbon emissions, ethical ratings, and compliance) affect their sustainability score, and to build a machine learning model to predict this score.

📊 Key Components
📦 1. Libraries Used
pandas – data loading and manipulation

matplotlib & seaborn – visualization

numpy – numerical computations

scikit-learn – machine learning (train/test split, RandomForestRegressor)

📈 2. Data Analysis & Visualization
Correlation matrix to identify related features

Scatter plot:

Carbon_Emissions_tCO2e vs Sustainability_Score

Insight: Brands with high emissions typically have lower sustainability

Regression plot:

Avg_Item_Price_USD vs Ethical_Rating

Insight: Slight positive trend – costlier items may reflect better ethics

🤖 3. Predictive Modeling
Target: Sustainability_Score

Features: Metrics like Compliance_Score, Transparency_Index, emissions, etc.

Model Used: RandomForestRegressor

Outcome: Feature importance visualization highlights which brand metrics most influence sustainability

✅ Conclusion
This project demonstrates:

Transparency and compliance are strong indicators of sustainability

Predictive modeling can assist brands in measuring and improving their ethical footprint

Data science can drive actionable insights to improve the sustainability of fast fashion

📁 Files in this Repository
DATA_ANALYSIS.ipynb – Jupyter notebook with full code and analysis

FDS_REPORT.pdf – Final report detailing methods, findings, and conclusion

🚀 How to Use
Clone this repo:

bash
Copy
Edit
git clone https://github.com/<your-username>/<repo-name>.git
Open DATA_ANALYSIS.ipynb in Jupyter or Google Colab.

Install required Python libraries:

bash
Copy
Edit
pip install pandas matplotlib seaborn scikit-learn
Run the notebook cells sequentially to explore and reproduce the analysis.


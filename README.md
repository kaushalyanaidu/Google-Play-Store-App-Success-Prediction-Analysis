# Google-Play-Store-App-Success-Prediction-Analysis


Project Overview
This project applies machine learning techniques to predict and analyze the success of mobile apps on the Google Play Store. With over 2.3 million apps in the dataset, we aim to uncover what factors contribute to app installs, ratings, churn, and removal risks, ultimately helping developers and stakeholders make smarter data-driven decisions.

Objectives
Identify key factors influencing app success and removal.
Predict user churn and app success based on app features.
Analyze the impact of pricing and monetization strategies.
Segment apps using unsupervised learning for strategic insights.

Dataset
Source: Kaggle (Google Play Store)

Size: 2.3M+ apps

Key Features:
Ratings, Installs, Category, Price, Ad-Supported, In-App Purchases

App Removal Status

User Engagement Metrics

Data Preprocessing
Missing values imputed (ratings, price)

Encoding of categorical variables (e.g., Category, Content Rating)

One-hot encoding for category features

Installs and Price converted to numeric

Exploratory Data Analysis
Social, Finance, and Productivity apps show the highest success rates.

Low-rated apps are more likely to be removed, especially in Finance & Gaming.

Free apps get more installs but face higher churn due to ads.

Paid apps see better retention but fewer downloads.

Machine Learning Models:

🔹 Logistic Regression
Predicts app success with high accuracy (AUC ≈ 0.966)

Key success drivers: Rating, Installs, Price, Ad-Support

🔹 Random Forest Classifier
Predicts user churn based on rating, ad-support, and updates

Churn accuracy: ~97%

🔹 K-Means Clustering
Segments apps based on engagement for targeted strategies

Best number of clusters: 6

Silhouette Score: 0.65

Key Business Insights:
High Ratings (4.0+) → Crucial for long-term success

Freemium Model → More effective than pay-to-download

Ad Control → Less intrusive ads reduce churn

Regular Updates → Strongly correlate with retention

Category Watch → Finance & Gaming need stricter compliance


Tools & Technologies:
Databricks (development environment),
Python, Spark ML, Google Colab,
Pandas, Seaborn, Matplotlib,
Scikit-learn for ML modeling

Project Files:
MLops_Report_FINAL.docx: Detailed report

MLops_FINAL_ppt.pptx: Presentation deck

FINAL_BIGDATAMLOPS.ipynb: Code used in Databricks (exported as Jupyter Notebook)


References
Kaggle Dataset - Google Play Store Apps

Spark ML Documentation

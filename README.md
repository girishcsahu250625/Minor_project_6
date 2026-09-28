# Minor_project_6
QuickCart Inventory Risk Prediction pipeline using Python &amp; Scikit-Learn. Features data extraction, cleaning, feature engineering, and time-based split. Evaluates Logistic Regression, Random Forest, and Gradient Boosting models for stockout risk classification (Safe, At-Risk, Imminent), achieving 95.7% accuracy with Gradient Boosting.

Key Features

- Data Extraction & Cleaning: Preprocesses raw inventory, order, and supplier data; handles missing values and outliers.
- Feature Engineering:Computes dynamic rolling demand, safety stock thresholds, lead-time variances, and turnover ratios.
- Time-Based Splitting: Evaluates models on temporal train-test splits to prevent data leakage and mimic real-world deployment.
- Model Evaluation & Comparison: Benchmarks Logistic Regression, Random Forest, and Gradient Boosting models.
- High Performance:Achieves 95.7% accuracy using the Gradient Boosting Classifier.

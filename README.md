🎬 Cinema Audience Forecasting — Machine Learning Project

This project predicts daily cinema audience counts for thousands of theaters using advanced feature engineering and regression models. It was developed for the Kaggle: Cinema Audience Forecasting Challenge.

🚀 Key Highlights

Applied time-series and contextual feature engineering

Created lag + rolling window statistics and cyclic seasonal features

Theater-level encodings (no data leakage)

Used Ridge Regression + Gradient Boosting Blend

Achieved 0.356 R² on Kaggle Leaderboard (above cutoff)

🧠 Tech Stack

Python, Pandas, NumPy

Scikit-Learn

Matplotlib / Seaborn (EDA)

🛠 Model Flow

Load booknow_visits historical data

Extract date-based and temporal features

LabelEncode theaters for efficient modeling

Train using time-based validation

Model blending for improved performance

Predict audience for test dates

📊 Results

Validation R²: ~0.48

Kaggle Leaderboard R²: 0.356

📂 Dataset

Due to license restrictions, datasets are available here
🔗 [https://drive.google.com/drive/folders/100Emj31FDRNXCwFAY8BxnEWOEbJfSMJb?usp=sharing]

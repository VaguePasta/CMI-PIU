# CMI-PIU
 Submission for https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use
 
 **Team name: VG**

 Model used: XGBRegressor from XGBoost.

 ### Methods used:
 - Data Preprocessing: By carefully handling missing data and eliminating irrelevant features, we reduced noise in the dataset and improved model performance

 - Feature Engineering: We created new features from the existing ones to enhance the model's ability to identify patterns

 - Model Selection and Optimization: XGBoost – an ensemble model based on decision trees – which improved accuracy and reduced overfitting through boosting and regularization techniques.

 - Actigraphy Data: Only included actigraphy data (Enmo, light, angle Z) when there was a clear correlation, using aggregated statistics (mean, median, and standard deviation) to prevent unnecessary complexity without significant improvements.
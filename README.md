#✈️ Flight Price Prediction using Machine Learning

Objective:
To build a machine learning model that predicts flight prices based on various features like journey date, departure time, arrival time, duration, airline, stops, and route.

Key Steps:
Data Reading & Cleaning: Loaded the dataset and handled missing values through appropriate imputation techniques.
Date & Time Feature Engineering: Extracted day, month, and weekday from Date_of_Journey. Processed Dep_Time and Arrival_Time to extract hour and minute for temporal insights.
Duration Processing: Split the Duration column into duration_hours and duration_minutes for better model interpretability.

Exploratory Data Analysis:
Analyzed flight departure patterns.
Explored how duration impacts price.
Investigated routes where Jet Airways is frequently used.

Encoding Techniques:
Applied one-hot encoding from scratch.
Used target-guided encoding for categorical variables to boost model performance.
Created custom mappings for features like Total_Stops.

Outlier Detection & Feature Selection:
Identified outliers using Data Analysis & handled outliers using median imputation to improve model performance.
Used statistical methods (Mutual Information) and model-based techniques to identify important features.

Modeling & Automation:
Built and saved the ML model.
Automated the ML pipeline !
Applied hyperparameter tuning using RandomizedSearchCV to improve model accuracy.

Outcome:
Successfully created a robust flight price prediction model with a well-engineered feature set and optimized ML pipeline.

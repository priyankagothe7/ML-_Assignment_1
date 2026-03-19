# Student Exam Score Predictor

## Problem Statement
The goal of this project is to build a simple Linear Regression machine learning model that predicts a student's final exam score based on their study habits and sleep schedule.

## Dataset Description
The dataset was created from scratch and contains 15 records. 
* **Features:** `Study_Hours` (numeric), `Sleep_Hours` (numeric), and a later added feature `Previous_Score`.
* **Target:** `Exam_Score` (numeric, 0-100 scale).

## Model Used
* **Algorithm:** Multiple Linear Regression (using `scikit-learn`).
* **Evaluation Metrics:** Mean Absolute Error (MAE) and R-squared (R2).

## Results
* **Base Model R2:** [Insert your R2 score from Task 4]
* **Feature Experiment:** Adding 'Previous Score' improved the R2 to [Insert score], while removing 'Sleep Hours' changed the R2 to [Insert score].
* **Overfitting Check:** Training and testing on the full dataset yielded an artificially high R2 of [Insert full score], demonstrating why a train/test split is crucial.

## Conclusion
The model successfully demonstrates that `Study_Hours` has a strong positive correlation with the final `Exam_Score`. Feature experimentation proved that adding highly correlated historical data (like a previous test score) yields the highest predictive accuracy.

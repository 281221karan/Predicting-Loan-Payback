This was a COMPETITION on kaggle: https://www.kaggle.com/competitions/playground-series-s5e11/overview

**Welcome to the 2025 Kaggle Playground Series! We plan to continue in the spirit of previous playgrounds, providing interesting and approachable datasets for our community to practice their machine learning skills, and anticipate a competition each month.**
**Your Goal: Predict the probability that a borrower will pay back their loan.**
_________________________________________

In this competition i did EDA and understand the data using graphs and the final model i submited was a ensemble model. So i basically combine 3 model (Catboost, LightGBMClassifier, XGBoost) and performing the K-FOLD approach to train these three models and the combining their outputs to train the meta model (Linear Regression) and i got sudden boost in ROC metrics from 0.78975 to 0.91759 and by further optimizing the model i got my best score of 0.92454 and got a rank of 941 out of 3000

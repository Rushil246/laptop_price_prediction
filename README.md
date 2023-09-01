# laptop_price_prediction
Introduction
This project predicts the price of a laptop based on its specifications. The project uses a machine learning model trained on a dataset of laptop prices and specifications.

The project was created to help users find the best laptop for their budget. The price prediction model can be used to estimate the price of a laptop before making a purchase.

Dataset
The dataset used to train the price prediction model was obtained from Kaggle. The dataset contains 10,000 rows of data, each of which represents a laptop. The dataset includes the following features:

Brand
Model
Processor
RAM
Storage
Display size
Operating system
Weight
Price
Data cleaning
The dataset was cleaned to remove any outliers, missing values, or duplicate data. The following steps were taken to clean the data:

Outliers were identified and removed using the Tukey method.
Missing values were imputed using the mean value for each feature.
Duplicate data was removed.
Model
The machine learning model that was used to predict the price of a laptop is a random forest regressor. The random forest regressor is a supervised machine learning algorithm that builds multiple decision trees to make predictions.

The random forest regressor was trained on the cleaned dataset using the scikit-learn library. The model was tuned using grid search to optimize the hyperparameters.
Future work
The following improvements could be made to the project in the future:

The dataset could be expanded to include more data points.
Other machine learning algorithms could be used to improve the accuracy of the price prediction model.
The web application could be improved to make it more user-friendly.

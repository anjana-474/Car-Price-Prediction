# Car-Price-Prediction

This project aims to predict the selling price of used cars using linear regression. By analyzing various features of the cars, such as year, kilometers driven, fuel type, and more, we build a model that helps estimate car prices

# Dataset

The dataset consists of the following columns:
- Brand: The make of the car.
- Model: Specific model of the car.
- Year: Year of manufacture.
- Selling_Price: Price at which the car is being sold.
- KM_Driven: Kilometers driven by the car.
- Fuel: Type of fuel used (Petrol/Diesel).
- Seller_Type: Type of seller (Individual/Dealer).
- Transmission: Transmission type (Manual/Automatic).
- Owner: Ownership status (First/Second Owner, etc.).

# Library Packages

- pandas
- scikit-learn
- numpy
- matplotlib

# Data Preprocessing

Feature Encoding: Convert categorical features like Fuel, Seller_Type, Transmission, and Owner into numerical values using one-hot encoding. <br>
Data Splitting: Divide the dataset into training and testing sets.

# Model Training

Utilize the linear regression algorithm to train the model on the training data. <br>
The model learns the relationship between the features and the selling price.

# Evaluation
Evaluate the model's performance on the testing set using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²). <br>
Analyze the coefficients to understand the influence of each feature on the car prices.

# Conclusion
This project demonstrates how linear regression can be used effectively to predict car prices. The model's insights can be valuable for both buyers and sellers in the used car market.




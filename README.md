**🚗 Car Price Prediction**

This project aims to predict the prices of used cars based on various features such as brand, model, year, fuel type, and more. 
Utilizing machine learning techniques, it provides an interactive web application where users can input car details and receive an estimated price.

**🧠 Features** 

-->Data Analysis: Exploratory Data Analysis (EDA) performed using pandas and matplotlib to understand data distributions and relationships.
-->Model Training: Implemented regression models (e.g., Linear Regression) to predict car prices.
-->Web Interface: Developed a user-friendly interface using Flask to input car details and display predicted prices.
-->Model Serialization: Trained model saved using pickle for efficient loading during inference.

**📊 Dataset**
The dataset Cardetails.csv includes various features of used cars, such as:

Name: Car brand and model
Year: Year of manufacture
Selling_Price: Price the car is being sold for
Present_Price: Current ex-showroom price
Kms_Driven: Kilometers driven
Fuel_Type: Type of fuel used
Seller_Type: Type of seller (Dealer/Individual)
Transmission: Manual or Automatic
Owner: Number of previous owners

📈 Model Training
The Jupyter Notebook Car_Price_Model.ipynb contains the steps for:
-->Loading and preprocessing the dataset
-->Performing EDA to understand data patterns
-->Training regression models to predict car prices
-->Evaluating model performance using metrics like R² score
-->Saving the trained model using pickle

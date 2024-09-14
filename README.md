# House Price Prediction Using Machine Learning

This project predicts house prices in Bangalore using a machine learning model. The project utilizes a linear regression model to estimate prices based on various input features like the number of bedrooms, bathrooms, total square footage, and location.

## Features

- **Data Preprocessing**: Handles missing data and applies one-hot encoding for categorical variables.
- **Linear Regression Model**: Trained to predict house prices based on input features.
- **Prediction Function**: Predicts house prices based on user inputs such as location, square footage, and the number of rooms.
- **Exported Model**: The trained model is saved as a pickle file for future use.
- **Location Data**: Location and feature information are exported in JSON format to aid prediction applications.


##Installation: Clone the repository with `git clone https://github.com/yourusername/house-price-prediction.git`. Install dependencies with `pip install -r requirements.txt`.

##Usage: To make a prediction, load the saved model and JSON column data, then call the `predict_price()` function, providing the necessary parameters like `predict_price('Indira Nagar', 1000, 2, 2)`.

##Files: `main.ipynb` - Jupyter notebook containing all the code and steps to train the model. `bangalore_home_prices_model.pickle` - Saved machine learning model. `columns.json` - JSON file with location and feature information.

## License
This code is provided as-is for educational and research purposes. You are free to use, modify, and distribute this code under the terms of your own licensing agreement.


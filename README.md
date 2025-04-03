# Car Price Prediction

## Overview
This project uses Machine Learning to predict the selling price of a car based on various factors like model year, mileage, fuel type, transmission, seller type, and ownership history. The model is built using Python and the RandomForestRegressor algorithm.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset
The dataset should be in CSV format and must contain the following columns:
- `year` - Manufacturing year of the car
- `selling_price` - Actual selling price of the car
- `km_driven` - Kilometers driven
- `fuel_type` - Type of fuel (Petrol, Diesel, etc.)
- `transmission` - Transmission type (Manual, Automatic)
- `seller_type` - Type of seller (Dealer, Individual)
- `owner` - Ownership history (First owner, Second owner, etc.)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/car-price-prediction.git
   cd car-price-prediction
   ```
2. Install dependencies:
   ```sh
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Ensure you have the dataset (`car_data.csv`) in the project directory.

## Usage
Run the script to train the model and predict car prices:
```sh
python car_price_prediction.py
```

## Model Evaluation
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Visualization
The project includes a scatter plot comparing actual vs. predicted prices for better analysis.

## Future Enhancements
- Integration with a web interface
- More advanced machine learning models
- Feature engineering to improve accuracy

## License
This project is open-source and free to use.


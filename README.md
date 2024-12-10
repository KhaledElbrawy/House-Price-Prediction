
# House Price Prediction

This project uses machine learning techniques to predict house prices based on various features of the property. The model employs the Boston House Price dataset and trains an XGBoost regressor to achieve accurate predictions.

## Features
- Load and preprocess the Boston House Price dataset.
- Visualize dataset correlations using heatmaps.
- Train an XGBoost model and evaluate its performance on training and testing data.

## Requirements

To run this project, ensure you have the following installed:
- Python (>= 3.7)
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `xgboost`

## Installation

1. Clone the repository or download the `House Price Prediction.py` script.
2. Install the required libraries by running the following command in your terminal:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost
   ```

3. Run the script:
   ```bash
   python House\ Price\ Prediction.py
   ```

## File Structure

```
House Price Prediction
├── House\ Price\ Prediction.py  
└── README.md                   
```

## Usage

1. Run the script to load and preprocess the dataset.
2. Visualizations such as heatmaps will help you understand feature correlations.
3. The XGBoost model will train on the dataset and provide metrics like R² score and Mean Absolute Error for evaluation.

## Results

The script outputs:
- Heatmap of feature correlations.
- Performance metrics for training and test datasets.
- Scatter plots showing predicted vs. actual prices.

## Notes

This project uses the `sklearn.datasets.load_boston` dataset, which may be deprecated. If you encounter issues loading the dataset, consider replacing it with an alternative dataset or library.

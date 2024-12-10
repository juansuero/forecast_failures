# Forecast Failures: Overfitting Detection Project

My first ML project. I don't really know what I'm doing, and the project is not finished, so don't trust anything you see or read too much. This project demonstrates how to detect and analyze overfitting in financial forecasting models using stock price data. It provides a practical introduction to machine learning concepts through stock price prediction.

## Overview
The project walks through the complete machine learning workflow:
- Data collection using Yahoo Finance API
- Data preprocessing and visualization
- Model training and evaluation
- Overfitting detection and mitigation
- Model comparison and visualization

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/forecast_failures.git
cd forecast_failures
```
2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate 
```
3. Install required packages:
```bash
pip install -r requirements.txt
```
## Project Structure
```bash
forecast_failures/
│
├── data/                # Data directory
│   └── raw/            # Raw data files
│
├── notebooks/          # Jupyter notebooks
│   └── market_data.ipynb
│
├── results/            # Output directory
│   └── plots/         # Saved visualizations
│
├── requirements.txt    # Project dependencies
└── README.md          # Project documentation
```
## Usage
1. Open the Jupyter Notebook:
```bash
jupyter notebook notebooks/market_data.ipynb
```
2. Run through the cells to:
- Fetch stock data from Yahoo Finance
- Preprocess and visualize the data
- Train different regression models
- Compare model performance
- Analyze overfitting
## Models Implemented
- Linear Regression (baseline)
- Polynomial Regression (to demonstrate overfitting)
- Ridge Regression (with regularization)
## Key Features
- Data fetching and preprocessing
- Time series visualization
- Model comparison
- Overfitting analysis
- Noise resistance testing
- Performance visualization
## Results
The project demonstrates:
- How polynomial regression can lead to overfitting
- How regularization helps prevent overfitting
- Model performance comparison under different conditions
- Impact of noise on predictions
## Dependencies
- numpy
- pandas
- matplotlib
- scikit-learn
- yfinance
## Contributing
Feel free to:
- Submit issues and feature requests
- Fork the repository
- Submit pull requests
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Data provided by Yahoo Finance



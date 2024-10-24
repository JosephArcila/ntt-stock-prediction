# NTT Stock Price Prediction

## Overview
Machine learning model for predicting NTT stock prices using LSTM neural networks and ensemble methods.

## Project Structure
```
ntt-stock-prediction/
├── data/                    # Stock price data
├── notebooks/              # Jupyter notebooks with analysis
├── src/                    # Source code
└── presentation/          # Final presentation materials
```

## Setup
```bash
# Clone repository
git clone https://github.com/yourusername/ntt-stock-prediction.git
cd ntt-stock-prediction

# Install requirements
pip install -r requirements.txt
```

## Data
The project uses historical NTT stock price data including:
- Daily closing prices
- Opening prices
- High/Low prices
- Trading volume

## Models
Three models were evaluated:
1. Original LSTM (Best performer)
   - R² = 0.993
   - MSE = 0.000453
2. Enhanced Bidirectional LSTM
   - R² = 0.926
   - MSE = 0.004884
3. Ensemble Model
   - R² = 0.970
   - MSE = 0.001946

## Running the Code
1. Place stock price data in `data/` directory
2. Run the notebook in `notebooks/` for complete analysis
3. Presentation materials available in `presentation/`

## Results
The original LSTM model achieved the best performance with:
- Lowest MSE (0.000453)
- Highest R² score (0.993)
- Most consistent predictions (MAE: 0.014790)

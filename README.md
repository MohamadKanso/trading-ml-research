# Stock-Analysis-ML

Simple stock analysis and prediction using Python, ML, and financial data.

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logo=xgboost&logoColor=white)

## Features

📈 **Data Analysis**
- Real-time stock data fetching
- Technical indicators
- Risk metrics calculation

🤖 **Machine Learning**
- Random Forest predictions
- XGBoost models
- Feature engineering

📊 **Visualization**
- Interactive price charts
- Performance metrics
- ML model comparison

## Requirements

```txt
yfinance
pandas
numpy
scikit-learn
xgboost
plotly
```

## Example Usage

```python
from stock_analyzer import QuantFinancialAnalysis

# Initialize
tickers = ['AAPL', 'MSFT', 'GOOGL']
analysis = QuantFinancialAnalysis(tickers)

# Run analysis
analysis.fetch_data()
analysis.calculate_risk_metrics()
analysis.train_ml_models()

# Visualize
analysis.create_all_visualizations()
```

## Output Examples

### Stock Analysis Dashboard
[Add screenshot of your main dashboard]

### ML Predictions
[Add screenshot of prediction results]

### Performance Metrics
[Add screenshot of performance metrics]

## License

MIT

---
Made with 💻 and ☕

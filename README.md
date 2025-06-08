# Time Series Forecasting with ARIMA

This project demonstrates time series analysis and forecasting using ARIMA models. It focuses on modeling Amazon stock price data over time, applying essential preprocessing steps, and evaluating forecasting performance.

## Project Highlights

- Time series decomposition and visualization
- Stationarity testing (ADF test)
- ACF and PACF analysis
- Parameter selection for ARIMA (p, d, q)
- Forecasting and performance evaluation

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- statsmodels
- Jupyter Notebook

## File Structure

```
ARIMA_analysis.ipynb            # Main notebook with full analysis
AMZN_data_1999_2022.csv         # Time series dataset (Amazon stock prices)
```

## Running the Notebook

To run the notebook locally:

1. Clone the repository:
   git clone https://github.com/LidanAvisar/Time-Series-with-ARIMA.git
   cd Time-Series-with-ARIMA

2. (Optional) Create a virtual environment:
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install required packages:
   pip install -r requirements.txt

4. Launch the notebook:
   jupyter notebook ARIMA_analysis.ipynb

## Author

Lidan Avisar  
Machine Learning Developer  
https://github.com/LidanAvisar

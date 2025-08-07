📈 HBL Stock Price Analysis and Forecasting (2020–2026)
This project provides a complete pipeline for exploratory data analysis, visualization, and forecasting of Habib Bank Limited's (HBL) stock prices listed on the Pakistan Stock Exchange (PSX) using SARIMAX time series modeling.

The project uses data from Yahoo Finance and includes:

Candlestick visualization

Anomaly detection

Stationarity tests

SARIMAX forecasting

Model evaluation with MAE and RMSE

🔧 Tools & Libraries
Python

pandas, numpy

matplotlib, mplfinance

statsmodels

scikit-learn

yfinance

🧠 Project Highlights
1. 📥 Data Collection
Stock data for HBL (HBL.KA) fetched using yfinance from Jan 2020 to Jan 2024.

2. 📊 Exploratory Data Analysis
Summary statistics and info

Missing value detection

Correlation matrix

Anomaly detection using z-scores

3. 🕯️ Candlestick Charting
Interactive selection of year and quarter

Candlestick plots using mplfinance with volume overlay

4. 🔬 Stationarity Check
ADF test to check for stationarity before modeling

5. 🔁 SARIMAX Forecasting
Time series forecasting using SARIMAX model

Forecasting future prices up to June 2026

Specific forecasts for:

1st September 2025

1st December 2025

1st June 2026

Forecast uncertainty visualized using confidence intervals

6. 📉 Model Evaluation
Trained on data up to July 2023, tested on Jul 2023 – Jan 2024

Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) calculated

Forecast vs Actual comparison with overlayed plots

📌 How to Use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/hbl-stock-forecasting.git
cd hbl-stock-forecasting
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook or Python script.

Note: The candlestick chart section requires manual input of year and quarter for interactive plotting.

📈 Example Output

Forecast with target future dates highlighted

📁 Project Structure
bash
Copy
Edit
hbl-stock-forecasting/
│
├── hbl_stock_analysis_forecasting.ipynb   # Main notebook
├── README.md                              # This file
├── requirements.txt                       # Dependencies
└── forecast_plot.png                      # (Optional) Example plot
📉 Evaluation Metrics
Metric	Value
MAE	XX.XX
RMSE	XX.XX

(Actual values printed in notebook output)

🔮 Forecasted Prices (Selected Dates)
Date	Forecasted Price (PKR)	95% CI Lower	95% CI Upper
01-Sep-25	XX.XX	XX.XX	XX.XX
01-Dec-25	XX.XX	XX.XX	XX.XX
01-Jun-26	XX.XX	XX.XX	XX.XX

(Exact values printed at the end of the notebook)

📬 Contact
For questions or collaboration:

Qasim Shafiq

Email: qasimshafiq4369@gmail.com

LinkedIn: linkedin.com/in/qasim-shafiq

Let me know if you want:

A requirements.txt file

This converted into a .md file

Help uploading this to GitHub and linking plots properly

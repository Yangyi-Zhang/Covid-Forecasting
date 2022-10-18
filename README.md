# COVID-19 Case Forecasting
COVID-19 Case Forecasting in CA counties with Auto-Regressive (AR), Long Short Term Memory (LSTM), and the Hybrid of AR and LSTM.

This is the code for our study: A Hybrid  Predictive Model of COVID-19 Cases using Autoregressive Model and LSTM

Data_preprocessing: extract counties of interest and treat missing data.
- LSTM_single: code for single layer LSTM, examined on 8 counties, latest trials(88 days) and all trials between 2020-02-01 to 2022-09-05.
- LSTM_double: code for double layer LSTM, examined on 8 counties, latest trials(88 days) and all trials between 2020-02-01 to 2022-09-05.
- AR_and_single_LSTM: code for AR model and single layer LSTM, examined on 8 counties, latest trials(88 days) and all trials between 2020-02-01 to 2022-09-05. The data was presented in a comprehensive report. Notice that the Hybrid model in this file is NOT THE SAME as the  Hybrid model presented in report.
- visuals: code for visual comparison on AR, single LSTM, and Hybrid. Examined across several counties and trials.

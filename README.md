# An interpretable hybrid predictive model of COVID‐19 cases using autoregressive model and LSTM

This is the code for our study: An interpretable hybrid predictive model of COVID‐19 cases using autoregressive model and LSTM. ArXiv: \href{https://arxiv.org/abs/2211.17014}{2211.17014}.
In this study, we proposed an interpretable hybrid neural network and tested its performance on COVID-19 prediction tasks, compared with AutoRegression, LSTM (single layer, double layer), SVM, Random Forest, XGBoost, on data collected from 8 countries, over 790 days.

Files:
Data_preprocessing: extract counties of interest and treat missing data.
- LSTM_single: code for single layer LSTM, examined on 8 counties, latest trials(88 days) and all trials between 2020-02-01 to 2022-09-05.
- LSTM_double: code for double layer LSTM, examined on 8 counties, latest trials(88 days) and all trials between 2020-02-01 to 2022-09-05.
- AR_and_single_LSTM: code for AR model and single layer LSTM, examined on 8 counties, latest trials(88 days) and all trials between 2020-02-01 to 2022-09-05. The data was presented in a comprehensive report. Notice that the Hybrid model in this file is NOT THE SAME as the  Hybrid model presented in report.
- CI_last_trial: code for prediction on the latest data from all 8 counties. 100 runs on each trial. With uncertainty quantification.
- visuals_uncertain: code for visual comparison on AR, single LSTM, and Hybrid. Examined across several counties and trials. 100 runs on each trial. With uncertainty quantification.

4/9/2023 update:
- add folder worldStudy, which includes an additional study on COVID-19 prediction in 7 countries around the world with the 4 original models and 3 additional models: AR, LSTM, double layer LSTM, hybrid, SVM, Random Forest, XGBoost.
- data: original data we study in this project, also available on the official website of California state goverment and the World Health Organization (WHO), respectively.

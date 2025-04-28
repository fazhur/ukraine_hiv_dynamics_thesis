# Analysis of the Impact of Russia’s Full-Scale Invasion of Ukraine on HIV Dynamics Using Machine Learning Methods

This repository contains the code implementation for my bachelor thesis in Computer Science at the Ukrainian Catholic University.

## Project Aim

The goal of this work is to estimate how the full-scale war in Ukraine has influenced the HIV epidemic.  
This is achieved by:

- Tuning and validating ARIMA, Prophet, and LSTM models,
- Forecasting HIV incidence trends for the period after February 24, 2022,
- Comparing model forecasts with the officially reported statistics.

## Repository Structure

data/


├── hiv_aids_data_ukraine_2014_2024_by_oblast.xlsx  
    Official HIV statistics from the Public Health Centre of the Ministry of Health of Ukraine.  
    Source: [PHC Official Website](https://phc.org.ua/kontrol-zakhvoryuvan/vilsnid/statistika-z-vilsnidu/statistichni-dovidki-pro-vilsnid)

├── relative_hiv_new_by_oblast.xlsx  
    Calculated relative HIV incidence rates for all Ukrainian oblasts (2014–2024).

├── relative_hiv_new_ukraine.xlsx  
    General relative HIV incidence rates for Ukraine as a whole (2014–2024).

├── best_forecast_lstm.csv  
    Results from the best-performing LSTM model forecast.




### Notebooks

- **`arima_prophet.ipynb`**  
  Jupyter Notebook for:
  - Data visualization
  - ARIMA model tuning and evaluation
  - Prophet model tuning and evaluation

- **`lstm_tensorflow.ipynb`**  
  Jupyter Notebook for:
  - LSTM model architecture setup
  - Hyperparameter tuning
  - Training, validation, and performance evaluation

## Prediction results

![arima_prophet_lstm_test](https://github.com/user-attachments/assets/4697fcba-4eca-40b5-abb8-880b7f041514)


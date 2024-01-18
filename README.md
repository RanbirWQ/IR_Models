# IR_Models
Comparative Analysis of Single-Factor and Multi- Factor Short Rate Models
This project implements various interest rate models for forecasting future interest rates. The implemented models include Vasicek, CIR, Hull-White One-Factor, LIBOR Market Model (LMM), SABR-LMM, and HJM Multifactor.

## Models Implemented

1. **Vasicek Model**
    - Simulates interest rate paths using the Vasicek model.
    - Calibrates model parameters to historical data.
    - Performs Monte Carlo simulation for future interest rate forecasting.

2. **CIR Model**
    - Simulates interest rate paths using the Cox-Ingersoll-Ross (CIR) model.
    - Calibrates model parameters to historical data.
    - Performs Monte Carlo simulation for future interest rate forecasting.

3. **Hull-White One-Factor Model**
    - Simulates interest rate paths using the Hull-White one-factor model.
    - Calibrates model parameters to historical data.
    - Performs Monte Carlo simulation for future interest rate forecasting.

4. **LIBOR Market Model (LMM)**
    - Simulates interest rate paths using the LIBOR Market Model.
    - Calibrates model parameters to historical data.
    - Performs Monte Carlo simulation for future interest rate forecasting.

5. **SABR-LMM Model**
    - Simulates interest rate paths using the Stochastic Alpha Beta Rho (SABR) model in the LIBOR Market Model.
    - Calibrates model parameters to historical data.
    - Performs Monte Carlo simulation for future interest rate forecasting.

6. **HJM Multifactor Model**
    - Simulates interest rate paths using the Heath-Jarrow-Morton (HJM) multifactor model.
    - Calibrates model parameters to historical data.
    - Performs Monte Carlo simulation for future interest rate forecasting.
## Usage

Each model is implemented in a separate Python script. To run a specific model, execute the corresponding script. Make sure we have the required dependencies installed.

## Dependencies

To install the necessary dependencies, run:

pip install -r requirements.txt

# BL-LSTM
This repository contains code for portfolio optimization using the Black-Litterman model, with ESG (Environmental, Social, and Governance) constraints. The views on asset returns are generated using a Long Short-Term Memory (LSTM) neural network. This code is part of the work presented in the paper titled "Machine Learning for Sustainable Portfolio Optimization Applied to a Water Market", which is currently under review.
LSTM Model for Views: The LSTM model generates views (predicted asset returns) from historical price data.
Black-Litterman Model: The Black-Litterman model combines market information with LSTM-generated views to adjust expected returns and covariance.
Portfolio Optimization: The portfolio is optimized with ESG constraints.
How to Use:

    Train the LSTM model on historical price data to generate views.
    Run the script to optimize the portfolio based on the Black-Litterman model and ESG constraints.
    Analyze results in the generated DataFrames (results_weights_df and results_rets_df).

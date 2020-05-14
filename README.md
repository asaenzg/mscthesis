# MSc. Project

I compare the performance of a RNN and a VAR model for inflation forecasting across 5 economies: the United States, the Euro Area, the Netherlands, Chile and Mexico.

The 'Data' file contains monthly time series of inflation, nominal interest rates, money supply M2, output gap, unemployment rates, real wages and RER YoY changes for these countries.

The 'Models' file contain the data presentation, the different models used and the results of the proyect.

The models used in the project are listed below:

    1. Benchmark: an AR(1) model. 
    2. VAR: the VAR's order was selected with the AIC. 
    3. "Automatic" NN with nnetar: A multivariate perceptron. 
    4. "Manual" NN with keras: A multivariate RNN with a GRU hidden layer.

At the moment, the NN with keras is still under construction.

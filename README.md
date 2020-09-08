# MSc. Project: NN Approach to Inflation Forecasting

I compare the performance of a RNN and a VAR model for inflation forecasting across 5 economies: the United States, the Euro Area, the Netherlands, Chile and Mexico.

The 'Data' file contains monthly time series of inflation, nominal interest rates, money supply M2, output gap, unemployment rates, real wages and RER YoY changes for these countries.

The 'Models' file contain the data presentation, the different models used and the results of the proyect.

The models used in the project are listed below:

    1. Benchmark: an AR(1) model. 
    2. VAR: the VAR's order was selected with the AIC. 
    3. NN with keras: A multivariate RNN with a LSTM hidden layer.

Please, run first the 'data_presentation' file in order to load the data for the other R Markdown files.

The AR(1) and VAR models were built using RStudio, while the keras NN was developed using Python. The code files are in R Markdown and Jupiter Notebook format (.Rmd and .ipynb, respectively).

# Description of the code:
The code uses stock market data as input which mounted through google drive. The code uses the Adj Close column of the data to perform computations. It trains the LSTM, RF, and GBM models on the historical data and then tests it on different stock data and then makes predictions on the unseen data.
# Description of Input files:
The input files are csv files containing stock data. They should be mounted in the drive and the correct path to these files is to be specified in the code to access them. The data range of these files should be more than 1800 rows because this code is handling ten years of data and for that window size of 1800 was chosen.
# Inputs during execution:
The program requires no inputs during executions.
# Output of the program:
The output of the program is graphs showing training results and then testing results in which stock prices are predicted in historical context and also for the future days.

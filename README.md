# Forecasting-of-Forex-Market-Based-on-Deep-Learning-and-Hyperparameters-Optimization

## ABSTRACT
Time series forecasting has got an important role in today’s economy. We use daily index price data and directly use our own index features as the model inputs. Using Long Short-Term Memory (LSTM) we predict the daily closing price of the index based on the historical data available. Using KerasTuner These models were trained, and automatically evaluating different components and design decisions, and their results were measured. Finally, we analyzed and clustered our results in order to know the characteristics of each cluster.

## PROBLEM SPACE
Time series exist in many forms and sizes. small sample size, high noise, non-linearity, and non-stationarity. The noisy features mean an incomplete information gap between the previous index price and its volume with the future price. 
In this study, we will see if it is possible to create a model using a Long and Short-Term Memory Network that will predict index price with a lower percentage of error. Also, we will see how accurate LSTM prediction is when compared to these models. 

## AIM OF WORK
Our primary goal is to investigate how well the LSTM algorithm predicts index prices. Therefore, the real question is not about whether they work or not, but rather how well an LSTM model can forecast the index adjusted closing price and determine the error percentage compared to the actual data.  

## METHODS
Long-and-Short-Term Memory Network (LSTM) – figure 1.
Find the Optimal Hyperparameters Using KerasTuner – figure 2.
Cluster the 100 model Hyperparameters table using K-Mean Algorithm.


## RESULTS
The price movement forecast 1400 trading days – figure 3.
Result of 100 models and their details – figure 4.

## CONCLUSION
A predictive model based on real-time series data was developed. The long short-term memory algorithm was selected since it is a well-known algorithm for sequence learning. Also, we tuned the model architecture and hyperparameters using KerasTuner. Finally, we cluster the results and know the characteristics for each cluster. 

## FUTURE WORK
many factors influence index movement, including macroeconomic events, market noise, investor attitude, and so on., we believe it is unwise to forecast the price purely based on the index historical data only. we should construct a hybrid model in which we employ sentiment analysis.




  










# Forecasting-of-Forex-Market-Based-on-Deep-Learning-and-Hyperparameters-Optimization

## ABSTRACT
Time series forecasting has got an important role in today’s economy. We use daily index price data and directly use our own index features as the model inputs. Using Long Short-Term Memory (LSTM) we predict the daily closing price of the index based on the historical data available. Using KerasTuner These models were trained, and automatically evaluating different components and design decisions, and their results were measured. Finally, we analyzed and clustered our results in order to know the characteristics of each cluster.

## PROBLEM SPACE
Time series exist in many forms and sizes. small sample size, high noise, non-linearity, and non-stationarity. The noisy features mean an incomplete information gap between the previous index price and its volume with the future price. 
In this study, we will see if it is possible to create a model using a Long and Short-Term Memory Network that will predict index price with a lower percentage of error. Also, we will see how accurate LSTM prediction is when compared to these models. 

## AIM OF WORK
Our primary goal is to investigate how well the LSTM algorithm predicts index prices. Therefore, the real question is not about whether they work or not, but rather how well an LSTM model can forecast the index adjusted closing price and determine the error percentage compared to the actual data.  

## METHODS
- Hybrid model based on Long-and-Short-Term Memory Network (LSTM).
- Finding the Optimal Hyperparameters Using KerasTuner.
- Clustering the 100 model Hyperparameters table using K-Mean Algorithm.
![Project Overview](https://github.com/AhmedIssa11/Forecasting-of-Forex-Market-Based-on-Deep-Learning-and-Hyperparameters-Optimization/blob/main/project_overview.png)


## RESULTS
The price movement forecast 1400 trading days – figure 3.
Result of 100 models and their details – figure 4.
![Best Result](https://github.com/AhmedIssa11/Forecasting-of-Forex-Market-Based-on-Deep-Learning-and-Hyperparameters-Optimization/blob/main/best_result.png)
![Evaluation Table](https://github.com/AhmedIssa11/Forecasting-of-Forex-Market-Based-on-Deep-Learning-and-Hyperparameters-Optimization/blob/main/evaluation_table.png)
![HP Table](https://github.com/AhmedIssa11/Forecasting-of-Forex-Market-Based-on-Deep-Learning-and-Hyperparameters-Optimization/blob/main/HP_table.png)

## CONCLUSION
To summarize, a comprehensive automatic system for predicting the index daily closing prices was constructed in this thesis. The decision has been made to use the deep learning technique as well as its different algorithms to develop a solid system that is recognized as a suitable system for different time series data patterns after investigating several techniques to determine the most useful methodology capable of resolving this particular problem. To begin, a predictive model based on real-time series data was developed. The long short-term memory approach was selected and implemented since it is a well-known algorithm for sequence learning methods in many applications. Also, we tuned the model architecture and hyperparameters using KerasTuner. Finally, we cluster the results and know the characteristics for each cluster. In this study, we outperformed previous stock prediction methods from different references. 

## FUTURE WORK
Financial markets are extremely complicated, and many factors influence index price movement, including macroeconomic events, market noise, investor attitude, and so on. so, when developing a deep learning model, we believe it is unwise to forecast the adjusted closing price purely based on the index historical data only. we believe that we should construct a hybrid model in which we employ sentiment analysis, for example, when trying to forecast the index price's volatility, we found that the prediction error was higher when the index price was volatile. As a solution to make the prediction correct and to be able to predict data patterns and at the same time predict the impact of news on the market, we will take into consideration more than just the history of index prices.




  










# Stock Trading Algorithm using a Neuro-Evolving Neural Network

In this project, I built a stock trading algorithm by modelling and forecasting stock prices of F&C Investment Trust PLC (FCT.NZ).  

I used a NeuroEvolution of Augmenting Topologies (NEAT) model, a hybrid approach incorporating genetic algorithms with evolving ANNs, to iteratively forecast one-day-ahead stock prices and incorporated the forecasts into various trading strategies.  
I used ARIMA forecasts as a benchmark, and no forecasts as a baseline in my trading strategies.  
The model that generated the highest returns of 1.2189 was the NEAT model with a trading strategy that used a crossover of forecast values and a 70-day fast SMA. 



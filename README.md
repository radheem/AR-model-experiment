# AR-model-experiment
I have conducted four experiments where first I checked if the data was stationary then plotted its ACF and PACF. Then I applied AR1, AR2, AR3 and AR4 and compared their results in visual plots.
The purpose of this experiment was to see how the predicted values varied as the order(lag) of AR was increased.
The AR model used is PyMC3 AR model which follows a bayesian approach. The sampler used is NUTS sampler.
The prior distribution of Beta is set to be a normal distribution with mean 0 and standard deviation 1 because beta ranges between -1 and 1, otherwise its not a stationary time series.

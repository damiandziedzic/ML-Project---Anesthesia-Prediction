# Machine Learning Project: Prediction of End-tidal Sevoflurane Gas Concentration of Patient During Surgery
In this project the current time (t) exhaled sevoflurane gas concentration is predicted based on features from the previous second (t-1) using the models:

* Multivariate Time Series Forecasting with Long Short-Term Memory (LSTM) Recurrent Neural Network
* Regular Multivariate Linear Regression

For each model, the predicted end-tidal sevoflurane gas concentration's correlation with the actual value is evaluated and shown below. Linear regression demonstrates improved performance compared to the LSTM recurrent neural network. Perhaps the LSTM model was too complex for the dataset and when there was noise or large variance in the data it was more difficult to track.


## Long Short-Term Memory (LSTM) Recurrent Neural Network Results
R<sup>2</sup> Values for the following surgical cases:
* Case 3: 0.9859930823562004
* Case 4: 0.9899826648126783
* Case 5: 0.930413736452069
![alt text](https://github.com/damiandziedzic/ML-Project---Anesthesia-Prediction/blob/master/Result%20Images/LSTM_results_picture.png)

## Linear Regression Results
R<sup>2</sup> Values for the following surgical cases:
* Case 3: 0.997497136050421
* Case 4: 0.9981166725629832
* Case 5: 0.9962023958701802
![alt text](https://github.com/damiandziedzic/ML-Project---Anesthesia-Prediction/blob/master/Result%20Images/Linear_Regression_results_picture.png)

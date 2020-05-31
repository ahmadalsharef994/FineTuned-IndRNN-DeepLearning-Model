# FineTuned-IndRNN-in-Stock-Markets
Our work aims to predict the future returns of the end of the next days using already given historical stock price data.

The first approach implemented in this project utilizes the Moving Average technique.  
The second approach was ARIMA which showed better performance and better accuracy than Moving Average.
The third approach was Long Short Term Memory networks. This model was trained on the data to give an acceptable loss and MSE.
The Fourth approach was Independent Recurrent Neural Networks (IndRNNs).
The fifth approach used was our upgraded fine-tuned IndRNN which we implemented by replacing the default activation function of IndRNN and this resulted in the enhancement of the model accuracy.

IndRNN model was never tested before in predicting financial data like stock market prices and hereby, we did our research work to check its efficiency within this purpose. We found out that it provides better accuracy than the other common approaches.
By our project, it would be easy for the investor to buy and sell stocks. Our results showcased that although prediction of price and trending is extremely challenging and depends on unpredictable events not only on the historical data, it is possible to make an intelligent system that can predict the market with an acceptable accuracy.

We used Python programming language to implement our work.
The deep learning approaches were involved using the Keras Regression Model.
The performance of approaches was measured and compared using the Mean Squared Error (MSE).

Final Results:
MSE (Mean Squared Error) of Each algorithm was:
Moving Average: 108
ARIMA: 55
LSTM: 53
IndRNN: 46
Our suggested Fine-Tined IndRNN: 44

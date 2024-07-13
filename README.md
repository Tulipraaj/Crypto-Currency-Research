# FoCID - Forecasting Cryptocurrency Investment Decision
Research work done during the internship at NIT - Trichy (2023 July)
This project mainly focuses on catching the complex patters of cryptocurrency prices and forecasting it to help investors make decisions on their trading strategies. The model uses an approach of a combination of Deep learning networks such as LSTM, GRU, Bi-LSTM and Ensemble Models. 

Parameters used in the Model
 - Price : Historical price of cryptocurrency.
 - Hash Rate : Computing power used up for securing the cryptocurrency network.
 - Block Size : The size of each block in the cryptocurrency’s blockchain.
 - Difficulty : Measure of challenge to mine a new block.
 - Market Capitalization : Value of the cryptocurrency traded on the market.
 - Mining Profitability : Potential profitability of mining the cryptocurrency.
 - Transaction : Information about volume of cryptocurrency transactions on the network.
 - Tweets : Social media activity and sentiment expressed on platforms like Twitter.

Model Description :
 - LSTM      - Two LSTM layers with 30 and 15 units
 - GRU       - Two GRU layers with 30 and 15 units
 - BiLSTM    - Two BiLSTM layers with 20 units each
 - GRU-LSTM1 - LSTM layer with 30 units GRU layer with 15 units
 - GRU-LSTM2 - LSTM layer with 15 units GRU layer with 30 units LSTM layer with 15 units
 - SVM1      - Linear kernel
 - SVM2      - Bagging
 - SVM3      - Boosting


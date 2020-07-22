New York Taxi Fare Prediction:

For a long time, I wanted to implement whatever I know and learnt about the data science. So, for starters I started with the basic dataset from Kaggle which is called as the New York Taxi Fare Prediction dataset. 

 Used linear regression model to predict taxi fares in New York City based on pick-up and drop-off locations.
 Performed feature engineering, tuned hyper parameters and evaluated multiple models.
 Analysed and visualized data to understand the importance of features and get various insights and patterns.



 PROXIMAL POLICY OPTIMIZATION FOR PORTFOLIO MANAGEMENT:

The basic idea behind this project was to experiment the use of Reinforcement learning with the time series data. I chose the stock trading data set as stock market is full of many unpredictable actions that determine change in data.  

Why Reinforcement? 
Since I wanted to build an agent that works well in unpredictable environment where the agent learns by interacting with environment and gradually improves performance by trial and error approach in the course of achieving a predefined goal.  PPO agents have been proven to work very well in the gaming environment that is full of unpredictable behaviors thus I wanted to test it in stock market. 

The goal set for the agent was to increase portfolio(sum of money available for trading + value of stock at any time) by making decisions to BUY,HOLD or SELL stocks at different price point and trend. 

Data set used: Apple stock
Results / Conclusions - 
The agent learned to trade.
The performance of the agent was not highly appreciable in terms of total portfolio optimized. 
Some assumption taken were ideal like 
- agent could trade (buy or sell) any number of times in a day). 
No track of any trend or price prediction taken into account. 
The agent was just trained and tested on a single data set that of APPL. 

Conclusion and future work - 
I would like to continue the research by researching on adding features like use of sentiment analysis and trend analysis to predict change in stock price then integrating those information to this trading bot and analyzing its performance. To encapsulate in a nutshell, a trading bot can be implemented with PPO agent that can trade however, additional features needs to be added for it to become smart and more accurate trading bot.

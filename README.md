### Project Title

Predicting stock prices at the close of market 

#### Executive summary

In the last ten minutes of the Nasdaq exchange trading session, market makers like Optiver merge traditional order book data with auction book data. This ability to consolidate information from both sources is critical for providing the best prices to all market participants. In this project we will develop a model that will accurately predict closing price movements of different stocks. 

#### Rationale
Each trading day on the Nasdaq Stock Exchange concludes with the Nasdaq Closing Cross auction. This process establishes the official closing prices for securities listed on the exchange. These closing prices serve as key indicators for investors, analysts and other market participants in evaluating the performance of individual securities and the market as a whole.

#### Data Sources
We will be using data source provided by Optiver on kaggle 

#### Methodology
We start with EDA. Our data anlysis includes checking all different values in the dataset. We also drop any nulls in the data. If there is data in text format we may need to convert to numbers in order to do modelling. 

I will also do some time series analysis on the model. I created a correlation matrix to see what major features impact target price and i will use that to build my models. 
As part of phase 1, i will build a simple model and add more as go more deeper in understaning towards captsone. 

#### Next steps
I need to do more splitting of data into train and test and the calculate mse on different models. 
I will build some models and compare output and errors 
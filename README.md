![home_image](https://user-images.githubusercontent.com/67566192/116619578-a18de780-a90e-11eb-9adc-17cdb9b48ede.jpg)
# Predicting Nike Stock Price

**Author**: Michael Tiernan

## Business Problem
With the explosion of trading apps like Robinhood, investing has never been as popular and widespread as it is right now. Given this vast market of beginner investors, there is more demand than ever for financial analysts as these new investors need a reliable source that they can trust with their recommendations and ultimately, their money. 

My consulting firm is doing a deep dive on Nike's stock as we are looking for value in a global apparel brand. 
1) Should we invest in Nike? 
2) When is the best time to invest in Nike? 

## Hypothesis
Null hypothesis (HO): Stock price will not have significant change in value when looking by month, as Nike is a provider of apparel and equipment for sports/lifestyle all year around.
Alternative hypothesis (Ha): Stock price has significant value change month to month

## Data
The data used in this analysis comes from [Yahoo Finance](https://finance.yahoo.com/quote/NKE/).  


## Method
For this project I stuck to the CRISP-DM method. After retrieving the data, I cleaned and performed EDA before modeling. 

For modeling, I chose to work with an ARIMA model as it accounts for all aspects of the Nike stock price data. 


## Findings
Nike has a constant upward trend therefore my model predicted that this will continue to be the case and you should invest. Historically, May and June are the best times to invest as it is before the holiday season and after the public interest has fallen following the reported earnings after the holiday season. 


## Recommendations
Invest now and hold for the long play.

Invest in May-June.

![Nike_predicted_graph](https://user-images.githubusercontent.com/67566192/116620348-b5861900-a90f-11eb-95dc-d2b2b84a11b4.png)

## Conclusion and Future Work
While my best model had a high AIC score, the MSE came in at 0.113 on the test data. We can reject the null hypothesis as we identified that May and June are when the stock price is historically the lowest and therefore the best time to invest. 

I am happy with the performance of my model, but with more time I would incorporate a neural network to uncover hidden layers/connections between Nike and its competitors to provide a more macro understanding of the market and Nike's position as a whole. I am also interested in incorporating NLP analysis on publications and social media to account for qualitative analysis surrounding Nike and the stock market as a whole. 
    

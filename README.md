![HOF_cover](https://user-images.githubusercontent.com/67566192/109255123-5990fe00-77c1-11eb-94e9-254e184c0b78.jpg)

# Predicting Nike Stock Price

**Author**: Michael Tiernan

## Business Problem
With the explosion of trading apps like Robinhood, investing has never been as popular and widespread as it is right now. Given this vast market of beginner investors, there is more demand than ever for financial analysts as these new investors need a reliable source that they can trust with their recommendations and ultimately, their money. 

My consulting firm is doing a deep dive on Nike's stock as we are looking for value in a global apparel brand. 
1) When is the best time to invest in Nike? 
2) month
3) day

## Hypothesis
Null hypothesis (HO): Stock price will not have significant change in value when looking by month, as Nike is a provider of apparel and equipment for sports/lifestyle all year around.
Alternative hypothesis (Ha): Stock price has significant value change month to month

## Data
The data used in this analysis comes from [Yahoo Finance](http://www.seanlahman.com/baseball-archive/statistics/).  


## Method
For this project I stuck to the CRISP-DM method. After retrieving the data, I cleaned and performed EDA before modeling. 

For modeling, I chose to work with an ARIMA model as it accounts for all aspects of the Nike stock price data. 


## Findings



## Recommendations



## Conclusion and Future Work
While my best model performed effectively with a 86% recall and 94% accuracy, it does not meet the requirement of within 5% to reject the null hypothesis. 

I am happy with the performance of my model, but with more time I would incorporate a neural network to uncover hidden layers/connections between Nike and its competitors to provide a more macro understanding of the market and Nike's position as a whole. I am also interested in incorporating NLP analysis on publications and social media to account for qualitative analysis surrounding Nike and the stock market as a whole. 
    
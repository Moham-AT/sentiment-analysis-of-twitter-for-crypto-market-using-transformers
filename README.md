# sentiment analysis of twitter for crypto market, using transformers
this code is a simple and straightforward way to know what's going on on twitter about the cryptos.

more precisely, i have used the twint library and transformer pipeline to analyse the sentiments of people on twitter in last 30 minutes. here, this analysis is about the bitcoin.
tweets are fetched from twitter by twint. then they are preprocessed and finally the sentiments of them(positive or negative) are calculated through the transformer pipeline. 

the analysis is then calculated in form of percent. for example 24% of all fetched tweets are positive and the others are negative. this number can be a good signal of what is going on in bitcoin curve in next minutes.

i have also calculated the avarage number of tweets per minute and avarage number of people who tweet per minute. this numbers also can be meaningful signals.

this signals can be analysed with another ML model in order to create a trader bot or for market forecasting .

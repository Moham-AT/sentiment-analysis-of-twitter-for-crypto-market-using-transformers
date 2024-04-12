# Real-Time Twitter Sentiment Analysis for Cryptocurrencies

This project provides a simple yet effective approach to understanding the current sentiment on Twitter regarding cryptocurrencies, specifically Bitcoin.

## Overview

Utilizing the **Twint** library, we fetch recent tweets related to Bitcoin. These tweets are then preprocessed and analyzed using a **Transformer Pipeline** to determine their sentiment (positive or negative). The sentiment analysis is conducted for tweets from the last 30 minutes, providing a real-time snapshot of public opinion.

## Analysis

The sentiment analysis results are presented as a percentage. For instance, if 24% of all fetched tweets are positive, the remaining 76% are inferred as negative. This ratio serves as a potential indicator of the upcoming trend in the Bitcoin market.

Additionally, we calculate the average number of tweets per minute and the average number of unique users tweeting per minute. These metrics can also serve as meaningful signals for market trends.

## Application

The signals derived from this analysis can be further processed using another Machine Learning model to develop a trading bot or for market forecasting purposes. This allows for more informed and data-driven decision-making in the volatile cryptocurrency market.

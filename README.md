# SP500-HMM-Predictions
## Abstract
Stock Markets are one of the most intricacy systems in the world, which are almost impossible to predict, and stock performances are an essential indicator of the strengths and weaknesses of the stock's corporation and the economy in general. Therefore, precisely predicting the stock price is of great research significance. This paper concerns four numeric attributes of the S&P 500 index as the research object, and the status and characteristics of the S&P 500 index are analyzed. We present two
prediction approaches implementing Hidden Markov Model (HMM) to predict stock price. One is implemented with the Gaussian HMM and the other is with Multipolinimial HMM. For multinomial HMM implementation, we converted the stock price into binary classes "Price Decline" and "Price Increase" and this is a novel approach. Both approaches applied observation window for better performance and evaluations were conducted for comparing performance with different window sizes.

Keywords: Hidden Markov model; The stock price index; Prediction;

# Introduction
## Problem Statement
Stock investment is considered a high-risk financial activity. Generally, most investors fail to consider factors in stock price variation or do not master professional knowledge and experiences related to investment. To enhance the quality and profitability of the decision-making process for investors, different methods for predicting stock market prices have appeared. Therefore, how to select the appropriate and accurate prediction method, and how to effectively use the stock information to help investors make decisions has become a primary issue in stock investment.
## Motivation
We have three main goals to achieve in this project. First, try to extract important information on stocks from their historical prices, including High, Low, Open, and Close price on every trading day’s record. Then, using the Hidden Markov Model combined with transition matrix and emission matrix to predict future trends of stock or future performance on four stock index. Last, we want to testify if the Hidden Markov Model is able to predict stock price precisely and be sensitive to the financial crisis between 2006 and 2016 this particular period.

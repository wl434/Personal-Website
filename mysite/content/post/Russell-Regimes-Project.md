---
date: 2022-02-28
linktitle: Predicting Market States

title: Predicting Market States
weight: 10
---

## Introduction:
This project aims to describe the overall "state" of the market (bull, bear, or neutral) via an ensemble (Hidden Markov + XGBoost) model used on the Russell3000 Index returns.

## Abstract:
Enormous amouts of wealth are changing hands at every moment in the financial markets. Consequently, an accurate forecast of the future is a valuable piece of information for any investor. While one might generally believe that one cannot accurately predict the price of an individual security, being able to predict the "state" of the market would unambiguously give investors an advantage over others. The idea of predicting the market state has been widely accepted and discussed by both academics and professionals. In this paper we review the popular definitions of Bull, Bear, and Neutral market states and create a method to predict the "state" of the market in real time. To do this we combine an unsupervised learning method (Hidden Markov Model) with a supervised learning method (XGBoost). We then deploy this hybrid model with a basic trading strategy on the Russell 3000 indel and analyze its performance. Our aim is not to find the most profitable trading strategy, but to demonstrate the potential of our model's predictions as part of a risk management strategy.


Link to Project Report: [Russell Regimes](https://github.com/wl434/Cornell-Project-Reports/blob/main/RussellRegimes.pdf)

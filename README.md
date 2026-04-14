# Trader Performance vs Market Sentiment Analysis

## Overview

This project explores how Bitcoin market sentiment (Fear and Greed Index) relates to trader performance. The analysis combines sentiment data with historical trade data to understand how market conditions influence profitability and risk.

## Objective

The goal is to examine whether traders perform differently during Fear and Greed phases, and to identify patterns in profit, win rate, and leverage usage.

## Data

* Fear & Greed Index: daily market sentiment classification
* Historical trader data: includes trade time, profit/loss (PnL), leverage, and trade details

## Approach

* Cleaned and prepared both datasets
* Merged them using date to align trades with market sentiment
* Analyzed performance across sentiment categories
* Compared behavior of top traders and average traders

## Key Findings

* Profitability tends to be higher during Greed phases
* Losses and volatility increase during Fear phases
* Higher leverage increases risk, especially in unfavorable conditions
* Top traders show more stable performance across different market sentiments

## How to Run

Open the notebook and run all cells in order. The analysis is self-contained.

## Files

* trader_sentiment_analysis.ipynb: main notebook
* README.md: project description

## Summary

The results suggest that market sentiment has a clear impact on trading outcomes. Recognizing these patterns can help in making more informed trading decisions.

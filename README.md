# Text-Classification-with-RNN---Twitter

## Background
This is one of my course projects of Deep Learning by professor Dave Wanik. <br/>
Leveraging text classification knowledge to classify a real-world problem is interesting and helps me uncover more insights from the social media. It is also a great start point to understand customer behavior patterns, evaluate product performance and even power demand forecasting. :)

## Problem Statement
With given tweets, I want to come up with RNN models to classify them into previously specified category. Starting from scraping 2000 tweets for Trump and 2000 for Obama, the final models will classify them into either 'Trump' or 'Obama' category. To improve model performance, I explored different model architectures.

## Actions
Part I: Data Preparation<br/>
 1.Scrape tweets and save to drive.<br/>
 2.Load the data from drive. <br/>
 3.Tokenize, pad the sequences and split data to training, validation and testing sets.<br/>
<br/>
Part II: Modeling<br/>
 1.Fit three models with different architectures.<br/>
 	Model1. LSTM + GRU<br/>
 	Model2. LSTM <br/>
	Model3. Conv1D + LSTM<br/>
 2.Evaluate models with confusion matrix reports.<br/>
<br/>
Part III: Analysis
	

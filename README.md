# Chess-White-Win-Prediction
Predict the result of a Chess game


## Overview:
	
Chess has been studied extensively for centuries, yet researchers and chess players continue to discover tactics and nuances that keep the game fresh. Chess is important for what it teaches us about strategy, risk, and consequences of actions. Using the Kaggle chess dataset that contains over 20,000 chess games, their outcomes, and other metadata, we want to answer the following question:
Can we predict the outcome of given chess game?

## Dataset Link:
https://www.kaggle.com/datasets/datasnaek/chess

**Data**

The data used to train the model was downloaded from [lichess.org](https://database.lichess.org/). We of course will need to process this data in a format that Machine Learning Algorithms Models can understand.

After downloading the dataset from lichess and decompressing it, we need to remove the unnecessary information such as player names, event names, time stamps, variations, comments, etc. The only information we want is the *final* result along with some statistics of the games.

## Training

The model was trained on 20,000 chess games. After training, the model achieved accuracy of ` 89.00% `.

## Results

![image](https://user-images.githubusercontent.com/71164642/184107281-b2db0aed-0dec-4101-b358-e8036cc31826.png)


Do :star: the project if you find it good enough. Thanks!

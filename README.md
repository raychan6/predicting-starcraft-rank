# Predicting StarCraft Player Rank Using Performance Data

## Question: Can I predict the rank of a StarCraft player based on their performance?

### The data (supervised) was obtained from [Kaggle](https://www.kaggle.com/datasets/danofer/skillcraft/data). The notebook file walks through my thought process, work, and findings. Here is a summary: 

- Performed EDA on dataset, which turned out to include much more low rank players
- Built a logistic regression model with 86% training accuracy and 84% testing accuracy and a random forest model with 96% training accuracy and 82% testing accuracy
- Preferred logistic regression model due to less overfitting and higher testing accuracy, but it predicts low rank players more accurately than high rank players
- Perhaps there is a smaller gap between low and high rank players than expected

<br> 

| ![](https://github.com/raychan6/predicting-starcraft-rank/blob/main/starcraft-logistic-regression.png) |
|:--:|
| *Confusion matrix of logistic regression model (0: low rank, 1: high rank)* |

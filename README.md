# Score_prediction_IPL

## Objective
The objective is to predict the total score of the cricket match by using various features. Dataset contains ball by ball data of the matches played during the 10 seasons of IPL.

## Important features

- venue : Stadium where match was played
- battingteam : Batting team name
- bowlingteam : Bowling team name
- runs : Runs scored by team till that point of instance
- wickets : Number of Wickets fallen of the team till that point of instance
- overs : Number of Overs bowled till that point of instance
- runslast5 : Runs scored in previous 5 overs
- wicketslast5 : Number of Wickets that fell in previous 5 overs
- striker : max(runs scored by striker, runs scored by non-striker)
- non-striker : min(runs scored by striker, runs scored by non-striker)
- total : Total runs scored by batting team at the end of first innings

## Algorithm vs accuracy

| Algorithm  | Accuracy % |
| ------------- | ------------- |
| Decision tree  | 86.73  |
| Linear regression  | 65.50  |
| Random forest regressor  | 99.06  |
| Lasso regression  | 65.05  |
| Support vector regressor  | 57.52  |
| Neural networks  | 85.70  |
![Accuracy](https://user-images.githubusercontent.com/93317185/188920564-e156a35a-20f7-4502-82df-88367f107c32.png)

## Final model

 - Random forest
    - Accuracy score - 99.06%
    - Mean Absolute Error (MAE): 1.66
    - Mean Squared Error (MSE): 8.34
    - Root Mean Squared Error (RMSE): 2.88

# March Madness 2022 Kaggle Competiton
### Competiton Summary 
* For many sports fans, March is a special month as the yearly college basketball tournament takes place in this month. Every single March millions of people fill out brackets trying to predict the results of all 63 games and everytime people fail misserably. This year I looked to use machine learning to predict the winner of every possible match-up in the March Machine Learning Mania 2022 - Men’s Kaggle competiton.
### Strategy
I wanted to try multiple different startegies including
1. A baseline model which looked only the average ranking of the team on the day before the tournament
2. A Logistic Regression Model using almost all stats available for both teams including wins and loses, points, field goals, three points, blocks assists etc
3. Logistic Regression, Decison Tree Classifier and SVC models using only the difference in WinPercent, PointDiff,	TrueShooting,	TotalReb,	Ast-Turn,	Blocks,	Steals, and	Rank between the two teams. 

### Results
![MM2022R](MM2022R.png)



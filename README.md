# Formula 1 prediction model 2025 - 2026

Here we are going to build a machine learning model which would predict the winner of each race as the season goes along.

## Australia Grand Prix - MELBOURNE
It was a pretty simple model. 
- The linear regression predicted Lando Norris to win, and followed by Oscar Piastri and Max Verstappen.
- The GradientBoostedRegressor predicted Oscar Piastri to win followed by Lewis Hamilton and Charles Leclerc
- Lando Norris won, and was followed by Max Verstappen and George Russell
- The MAE was poor for both models, considering I am only using one feature
- Next step would be to add more features

## China Grand Prix - SHANGHAI
- We added Sector times to the model
- The MAE error reduced for both models employed
- The Linear Regression predicted Fernando Alonso, Lance Stroll and Yuki Tsunoda to in this order as winners
- The GradientBoostedRegressor predicted Yuki Tsunoda, Max Verstappen and Alex Albon as winners.
- The winners were the McLaren duo Lando Norris and Oscar Piastri followed by George Russel
- The model is more useful, but needs more historical data such as rookies information and weather conditions

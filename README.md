# NBA-Research

## Summary
This notebook is an in depth analysis of the relationship between different stats and the winrate of a team in the NBA. Data is retrieved from the SportRadar API,
explored in depth using matplotlib.pyplot and seaborne, the transformed into a format usable by a machine learning model. A Neural Network is created, the hyperparameters are tuned, and the model is fit on training data, and tested on validation data. The predicitons are then used in conjuncture with the pysbr API's moneylines to substitute for the variables in the Kelly Criterion to determine the optimal fraction of the bankroll to bet on each team on any given day.

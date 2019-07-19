# FIFA-19
### Predicting the potential of players using the FIFA 19 dataset.
The aim of this project is to predict the potential of a player based on the dataset. The dataset contains the details of players, their nationality, and other attributes such as dribbling, acceleration, stamina, shot-accuracy, etc.
### Data Source
The players’ data for FIFA 19 can be found on kaggle.com. The dataset contains the players’ details with attributes that would be useful in predicting the potential of the player.
### Feature Selection
The following features have been chosen to predict the potential:
1. Age
2. International Reputation
3. Stamina
4. Strength
5. Aggression
6. Composure
7. Ball Control
8. Dribbling
9. Acceleration
### Target Variable
The potential of a player has been chosen as the target variable. The potential of a player represents how a player would perform keeping in view that the player remains injury free for most the duration of the season.
### Predictive Modelling
I have used Regression model to predict the potential of a player based on other attributes present in the dataset. Linear Regression using one independent variable, Multiple Regression and Polynomial Regression have been used to predict the Potential and their accuracy has been compared.

This model can be further analysed using clustering algorithms to create clusters of players with a certain potential. For example, players with a potential greater than 95 can be clustered into a ‘special’ category, while players with potential between 90 and 94 can be categorized as ‘exciting’, and so on.

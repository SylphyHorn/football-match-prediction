# football-match-prediction
## Data acquisition and processing
The data is scraped from www.besoccer.com.
Currently it takes the elo, the goals for and goals against for both teams as features. And the scores are processed and transformed into game results
## model training and tunning
A number of classification methods are applied and tunned for prediction. The random forest model performs the best with 50% accuracy. Considering a simple KNN model have 40% accuracy, this is a good improvement in terms of performance. These tunned models are saved as .joblib files for later use.

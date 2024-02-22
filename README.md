# Olympics
A ML Model to predict medals won by countries.
This includes creating a hypothesis, setting up the model, and measuring error using Python and Jupyter.

I used data from historical Olympic games and tried to predict how many medals a country will win based on historical and current data. The dataset consists of how many medals each country won at each Olympics. I used mean squared error for regression accuracy metric. It's the average of squared differences between the actual results and predictions.

This model works well for countries which have a high medal count, and compete in a stable number of events annually. For countries that get fewer medals, we'd have to build this model in a different way.

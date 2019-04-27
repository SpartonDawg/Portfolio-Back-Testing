# Portfolio-Back-Testing
Framework for pulling data for a portfolio of equities or currencies. Utilizes a random walker to find the best parameters to maximize risk adjusted returns. Currently using a MACD and SMA/LMA momentum-based strategy but is flexible.

Machine Learning Application - utilizes SKlearn to try and predict when to buy or sell an asset. The accuracy of the model would be equal to the amount of correct buys / buy opportunities. For example, if the model predicts to buy 2 times in the week, but only one prediction made money the accuracy is 50%. Does not factor in missed oppurtunities.

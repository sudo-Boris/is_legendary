# Is this pokemon legendary or not?

In this notebook we take a look at a simple binary classification task. We want to determine whether a Pokémon is legendary or not
based on its features such as effectiveness against other Pokémon types, its weight, and more.

## Results
We achieve an accuracy of 98% and an F1-score for non-legendary Pokémon of 0.99 and for legendary classification of 0.94!

## Challenges
The difficulty with this dataset is that it is heavily imbalanced: ~90% non-legendary Pokémon and ~10% legendary Pokémon.
By implementing the regularization techniques **data standardization**, **stratification on train-test split**,
**batch normalization**, and **dropout** we can combat this imbalance and achieve the results mentioned above!

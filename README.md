# Is-the-Mushroom-Poisonous

## About Dataset
The dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family. Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended.

## Steps Performed
1. Load the data.  
2. Separate the target, y and features, X from the dataset.  
3. Recode the target y, so that poisonous mushrooms are represented as 1 and edible mushrooms as 0.  
4. Transform the columns of the feature set X into a numpy array with a binary representation i.e, one-hot encoding.  
5. Conduct both a grid search to find an optimal hyperparameterization for a random forest classifier. Using accuracy as your method of model evaluation.  
6. Plot the mean test score versus hyperparameterization for the top 10 models found using grid search.  

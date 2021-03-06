# Food_Analysis

This is a simple exercise on a food dataset available
[here](https://tools.myfooddata.com/nutrition-facts-database-spreadsheet.php).
I am by no means an expert on nutrition, but I am curious about healthy food and food properties in general.
Since some plots are generated with [pyplot](https://matplotlib.org/stable/tutorials/introductory/pyplot.html), 
I have added a link to [nbviewer](https://nbviewer.org/) where those plots are rendered.

## [01_Food_Analysis_EDA](https://github.com/kauber/Food_Analysis/blob/main/01_Food_Analysis_EDA.ipynb)
nbviewer [link](https://nbviewer.org/github/kauber/Food_Analysis/blob/main/01_Food_Analysis_EDA.ipynb)

This is a basic EDA, in which I explored properties of the food using charts (boxplots, histograms, scatterplots),
and statistical methods such as Pearson correlation coefficient or PCA.

## [02_Food_Analysis_Calories_predictor_ML](https://github.com/kauber/Food_Analysis/blob/main/02_Food_Analysis_Calories_predictor_ML.ipynb)

In this notebook, I built a simple Machine Learning model that predicts caloric content of food based on their properties.
<br> I created an essential pipeline using the [scikit-learn](https://scikit-learn.org/stable/index.html) library, and [xgboost](https://xgboost.readthedocs.io/en/latest/) to build a regressor that will 
estimate caloric content of food.

## [03_Food_Analysis_Substitute_Recommender](https://github.com/kauber/Food_Analysis/blob/main/03_Food_Analysis_Substitute_Recommender.ipynb)

In this notebook, I show how to create a POC (proof of concept) food substitute recommender, writing a Python function
that uses Gower Distance (a good [overview](https://www.rdocumentation.org/packages/StatMatch/versions/1.4.0/topics/gower.dist) here) to estimate the most similar matches to a food we pass to it.
<br> This might have applications in cases in which we don't have or find a particular food, and we want an alternative with close
nutritional properties. <br>
The general concept of finding similar matches to a target has various applications in Data Science.
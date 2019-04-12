

We will build different types of supervised models in this workshop.

Ensure you at least follow the setup setups in the [previous lab](advanced.md).  We reuse this data.  

Please note that you will need to change file locations in some of these notebooks.  But not all.  

## Steps

1.  Create a classification model

* upload `Labs\classification.ipynb`
* complete the notebook

2. Build a Regression Model

Having built a classification model that predicts whether or not a flight will be late, you will now build a
regression model that predicts how late (or early) flights will arrive.

* `Labs\Regression.ipynb`


3. Pipeline Model

So far you have built models by calling the `fit` method on the algorithm class. Now you will use a Pipeline
class to encapsulate the transformers and estimators used by your model.

* `Labs\Pipeline.ipynb`

4. Working with Text features

All of your models to this point have used numeric columns for features.  We are going to work with the `data\tweets.csv` file.  You may want to look at this data with vscode or notepad first.  

* `Labs\TextAnalysis.ipynb`

## Knowledge Checks

* how would you create a "global" variable to hold your data file locations that can be referenced in any notebook?  
* why are pipelines beneficial in the real world?  
* for the tweets data we used a classifier (positive sentiment or negative sentiment).  Would it be better to use regression instead?  


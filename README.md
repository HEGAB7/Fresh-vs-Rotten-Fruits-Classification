# Fresh vs Rotten Fruits Classification

The dataset comes from [Kaggle](https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification)
<br>
There are 6 categories of fruits: fresh apples, fresh oranges, fresh bananas, rotten apples, rotten oranges, and rotten bananas.

## Steps:
* load the pretrained model inception V3
* Add our new layers
* Augment the data
* Freeze and fit the model
* Unfreeze and retrain the model
* Evaluate the model
* Make a pipline for easy use to predict the category by the image path

Data Analysis Examples
==========

This repository contains some examples of data analyses that I have performed  to highlight different aspects of modeling and prediction.

## Inference
### Mpg and transmission type
- This analysis looks at the 1974 *Motor Trend* data from the `mtcars` dataset in R's `datasets` package.
- The dataset's documentation is available [here](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/mtcars.html).
- It attempts to find out whether transmission type affects fuel consumption. To do this it finds the best **multiple regression** model of miles per gallon in terms of transmission type and other variables that is in line with the assumptions of multiple linear regression.

## Prediction
### The quantified self: proper lifting
- An accurate (<0.5% out of sample error) prediction model based on sensor measurement data from belt, arm, dumbbell, and forearm monitors is developed to predict whether dumbbell bicep curls have been performed correctly.
- The final model consists in a tuned **random forest** implementation validated with 10 fold cross-validation and tested on a large hold-out dataset.
- The dataset is from the [Groupware@LES](http://groupware.les.inf.puc-rio.br/har) research group. The data set contains 19,622 observations of 159 variables in which 6 participants from 20 to 28 years of age were asked to perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five ways: (i) exactly according to the specification, (ii) throwing the elbows to the front, (iii) lifting the dumbbell only halfway, (iv) lowering the dumbbell only halfway, and (v) throwing the hips to the front.
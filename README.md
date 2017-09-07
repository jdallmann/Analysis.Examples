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

## Dashboarding
### Market comparables app
- This "proof of concept" Shiny dashboard/web app, written in R, can be found at: [https://jdallmann.shinyapps.io/comparablesapp/](https://jdallmann.shinyapps.io/comparablesapp/).
- The app performs k-means clustering on two months of Winnipeg real estate data on different features of properties including:
    + latitude,
    + longitude,
    + living area,
    + year,
    + frontage,
    + whether the property has a garage.
- The original data was scrapped from the web, cleaned, imputed using k-nearest neighbors (k=2), and normalized before clustering. Code for the gathering and scraping process (in the form of bash and python scripts) are available on request.
- The github code repository for the app can be found [here](https://github.com/jdallmann/market.analysis/tree/master/comparablesApp).
- Code for a neural network based prediction algorithm with accuracy comparable to that of a real estate agent (agents are off by 10k on average, the app is off by 15k on average) is also available on request.
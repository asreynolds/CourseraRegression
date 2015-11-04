# Coursera Data Science 

## Regression Course Project

This is a basic exercise in linear regression. Please view my submission by clicking autovsmanual.pdf in this repository.

### Goal

This project addresses the question of whether automatic or manual transmission vehicles get better fuel efficiency. In the end, we find that manual transmission vehicles tend to get better fuel efficiency, but that this is mainly due to their tendency to be lighter vehicles.

### Data

We use the `mtcars` dataset provided in the R `datasets` package. This dataset requires no preprocessing, and so this project focuses mainly on regression techniques and diagnostics. The documentation for this dataset can be found [here](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/mtcars.html).

### Methods

We perform some initial exploratory analysis, including some basic plots and correlation computation. From this, we judge that the weight of the vehicle would make a strong and useful predictor for fuel efficiency. After building a simple linear regression model of fuel efficiecy with transmission type as the sole predictor, we compare this to a linear model where weight is included as a second predictor. We find that weight is far more significant than transmission type as a predictor of fuel efficiency.

We then evaluate the reliability of our linear models using some standard diagnostics implemented in R. These include checking for departure from normality and high-leverage points. No problems were detected, and so we conclude that the models are reliable.

### Plots

All plots are included in the Appendix of the report, starting at page 3.


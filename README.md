
<!-- README.md is generated from README.Rmd. Please edit that file -->
learningAnalytics
=================

**Author:** [Brad Boehmke](http://bradleyboehmke.github.io/)<br/> **License:** [GPL (&gt;= 2)](https://opensource.org/licenses/gpl-license)

`learningAnalytics` is an R package that provides a structured learning environment to deliver tutorials covering various statistical learning techniques.

Installation
------------

You can install `learningAnalytics` straight from GitHub with:

    if (packageVersion("devtools") < 1.6) {
      install.packages("devtools")
    }

    devtools::install_github("bradleyboehmke/leaningAnalytics")

Start Learning
--------------

`learningAnalytics` provides several tutorials covering common analytic techniques:

1.  "Hello": An introduction to `learningAnalytics`
2.  "EDA": Exploratory Data Analysis
3.  "Unsupervised": Principal Components Analysis & Cluster Analysis
4.  "Linear Regression": Linear Regression
5.  "Supervised Classification": Logistic Regression & Discriminant Analysis
6.  "Resampling": Leave-One-Out Cross-Validation, *k*-Fold Cross Validation, & Bootstrapping
7.  "Model Selection": Best Subset & Stepwise Selection for Linear Models

To start learning just use the `get_tutorial` function to activate the desired tutorial:

    library(learningAnalytics)

    get_tutorial("Hello")

Enjoy!

---
title: "README"
author: "Joshua A Hightower"
date: "October 25, 2015"
output: html_document
---

Project Getting and Cleaning Data
=================================

Repository for project in Getting and Cleaning Data

Read data from [Human Activity Recognition Using Smartphones Dataset](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) and return a tidy data set containing the mean for every variable per subject and activity.

Usage
-----

``` R
source("run_analysis.R")
tidyData <- run_analysis()
```

Documentation
-------------

Read [CodeBook](codebook.md) to find out more about `run_analysis`

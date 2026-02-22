# Chapter 3: When Data Visualization Lies

## Overview
This project explores how visualization choices can influence interpretation, even when the data doesn’t change.

I run through examples where tiny tweaks in visualization (like changing axis scales, picking different histogram bins, or filtering certain data) can make trends look different than they actually are. 

## Core question
How much can perception change based on visualization design alone?

## My Projects
* [**01_truncated_axis.ipynb**](./01_truncated_axis.ipynb) : This demonstrates how manipulating the Y-axis range can exaggerate small trends.![bar charts](./images/bar-charts.png)

* [**02_bin_manipulation.ipynb**](./02_bin_manipulation.ipynb) : This demonstrates how changing the width of bins in histograms can affect how we view data.![histograms](./images/histograms.png)

* [**03_correlation_illusion.ipynb**](./03_correlation_illusion.ipynb):
This demonstrates how cherry picking specific data subsets can hide strong negative correlations.![scatter plots](./images/scatter-plots.png)

## Data Source
This project uses a public cereal nutrition dataset from Kaggle containing sugar, fiber, and consumer ratings
 https://www.kaggle.com/datasets/crawford/80-cereals
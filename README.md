# VortexTech Data Science Internship. Week 1: Data Cleaning and Basic Visualization

## What this project does

This project takes an messy restaurant tips dataset from VortexTech and does a few things.

It identifies missing values in the restaurant tips dataset and handles them.

It also deals with rows in the restaurant tips dataset and fixes an incorrect data type in the restaurant tips dataset.

The project then produces five visualizations of the restaurant tips dataset.

These visualizations include a histogram of the restaurant tips dataset, a bar chart of the restaurant tips dataset, a pie chart of the restaurant tips dataset, another bar chart of the restaurant tips dataset and a line chart of the restaurant tips dataset.

Each visualization of the restaurant tips dataset has titles and axis labels.

The project also includes explanations of the patterns shown in each visualization of the restaurant tips dataset.

## Dataset

The `restaurant_tips_raw.csv` file is used for this project.

This file has 250 records of restaurant visits from VortexTech.

The file has some columns like `total_bill` `tip` and `size` which is the party size at the restaurant.

It also has some columns like `sex` `smoker` `day` and `time`.

The raw file has some problems like missing values, duplicate rows and a data-type issue with the `size` column which has stray whitespace.

## Files

There are two files for this project.

The `week1_data_cleaning_and_visualization.ipynb` file is the notebook for the project.

This notebook is already. Has all the outputs and charts visible.

The `restaurant_tips_raw.csv` file is the dataset used for the project.

## How to run

To run this project you need to do a things.

First you need to clone this repository from VortexTech.

Then you need to install some required libraries.

You can install these libraries by running the following command:

```

pip install pandas matplotlib seaborn jupyter

```

After that you need to launch Jupyter and open the notebook by running the following command:

```

jupyter notebook week1_data_cleaning_and_visualization.ipynb

```

Finally you need to run all the cells in the notebook from top to bottom.

You can do this by going to `Cell` and then clicking `Run All`.

## Summary of findings

After cleaning the restaurant tips dataset it has no missing values or duplicates.

The `size` column is also an integer column now.

The project found that most restaurant visits happen on weekend days like Saturday and Sunday and during dinner service.

It also found that the tip amount is closely related to the bill amount and increases with the party size, at the restaurant.

The restaurant tips dataset shows that the tip amount rises with the party size.

The total bill amount and the tip amount are closely related in the restaurant tips dataset.

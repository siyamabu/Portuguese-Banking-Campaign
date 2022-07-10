# Predicting If a Client Will Subscribe to A Portuguese Banking Campaign

![Status Update](https://img.shields.io/badge/Status-Complete-brightgreen) 
![GitHub top language](https://img.shields.io/github/languages/top/sverma1012/income-level?color=%23F37626&logo=Jupyter&logoColor=%23F37626&style=flat-square)
![Python version](https://img.shields.io/badge/Python%20version-3.10%2B-lightgrey)
![GitHub repo size](https://img.shields.io/github/repo-size/siyamabu/Portuguese-Banking-Campaign)
![License](https://img.shields.io/badge/License-MIT-green)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

Badge [source](https://shields.io/)

## Key findings



## Authors

- [@siyamabu](https://www.github.com/siyamabu)

**Language and Tools:**<br />
* Python :snake:
* Jupyter Notebook :notebook:
* GitHub :heart_eyes:

**Modules used:**<br />
* Pandas
* Scikit-learn
* Numpy
* Matplotlib
* Seaborn

**Environments Used:**<br />
* Windows 10 🪟

## Description 

This project consists of  that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.

## Table of Contents

  - [Motivation](#motivation)
  - [Data source](#data-source)
  - [Methods](#methods)
  - [Quick Glance at the Results](#quick-glance-at-the-results)
  - [Lessons Learned and Recommendations](#lessons-learned-and-recommendations)
  - [Limitations and What Can Be Improved](#limitations-and-what-can-be-improved)
  - [Explore the Notebook](#explore-the-notebook)
  - [License](#license)

## Motivation 

## Data Source

- [Bank Marketing](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

## Dataset Description

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to assess if the product (bank term deposit) would be ('yes') or not ('no') subscribed.The classification goal is to predict if the client will subscribe (yes/no) a term deposit.

## Methods

- Correlation Analysis
- Logistic Regression
- Decision Tree

## Quick Glance at the Results

Correlations between variables.

![heatmap](pictures/life_correlation_heatmap.png)

A comparison of the best results from each model.

![graphx](pictures/model_results.png)

The Residuals vs Predicted Strength for the best linear regression model.

![graph1](pictures/residuals_vs_predicted_linear_regression.png) 

The Observed Strength vs Predicted Strength for the best linear regression model.

![graph2](pictures/observed_strength_vs_predicted_strength_linear%20regression.png)

The Residuals vs Predicted Strength for the best decision tree regression model. 

![graph3](pictures/residuals_vs_predicted_decision_tree_regression.png)

The Observed Strength vs Predicted Strength for the best decision tree regression model.

![graph4](pictures/observed_strength_vs_predicted_strength_decision_tree_%20regression.png)

5 highest feature importance scores from the best decision tree model.

![graphy](pictures/feature_importance.png) 

## Lessons Learned and Recommendations

## Limitations and What Can Be Improved

## Explore the Notebook

To explore the notebook file [here](https://github.com/siyamabu/Life-Expectancy/blob/main/life_expectancy_prediction.ipynb)

## License

MIT License

Copyright (c) 2022 Siyabonga Mabuza

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Learn more about [MIT](https://choosealicense.com/licenses/mit/) license


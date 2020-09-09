# Covid-Markets
This project analyzes movements in Nasdaq and Bitcoin volatility parameters and correlates them to COVID news releases and check whether there is a pattern between financial market and the development of COVID pandemic.


## Motivation
The motivation of this study is to identify what has happened to the market due to this pandemic and help others see when and why the market changed.

This will help identify why the stock market has fluctuated these last few months and what event caused it.
This research may help predict what will happen to stocks/bitcoins when COVID-19 [3] cases increase or decrease in the future.
In case of a future pandemic, it will be better known as to what may occur to the stock market as new information arises and as the country responds.
Can help shareholders make decisions about their shares based on past events and fluctuations seen from the research.


## Problem Statement
Has COVID-19 cases and deaths affected the stock and cryptocurrency markets?


## Background


## Prerequisites

### Built With

* [Python](https://www.python.org/) - Language used.


### Libraries Required
The gathering and manipulation of the data was made in the Python language, utilizing colaboratory.
The Libraries that are require for this Python project to properly run are:

import seaborn as sns
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from scipy.stats import ttest_ind
from scipy.stats import mannwhitneyu
from scipy.stats import pearsonr
from datetime import datetime
from pandas.plotting import register_matplotlib_converters
register_matplotlib_converters()
%matplotlib inline

Each section of the code already has the import statements stablished for it to run.


### Gathering the data

The data for this project was gathered from the webpage: 

Nasdaq and Bitcoin Data: https://finance.yahoo.com/; https://www.barchart.com/

COVID-19 Data: https://shiny.rstudio.com/

COVID-19 Event date list: www.theguardian.com

## Methodology
To determine if COVID data and events affect financial markets, the following steps are followed:
1. Financial data, COVID data and COVID related news list are downloaded.
2. Merge price and volume data with COVID-19 data to form a combined date-based table.
3. Day plots were created base on price, volume and case data.
4. Created indexes base on COVID event list and add it to Day plots as vertical lines.
5. Calculate correlation values, do hypothesis tests and make it as  tables.
6. Do statistical analysis and get conclusions base on the value tables and graphs. 


## Text Findings

Our research tested whether COVID-19 events had, in general, an impact on the market volatility. Our research has indicated that there is a significant difference between event days and no event days in Bitcoin price change. Also, we have proven that, based on the correlation table, Nasdaq daily close prices have a moderate positive relationship with total cases and total deaths (globally and in the USA). Lastly, Bitcoin daily Volume has a moderate negative relationship with total cases and total deaths.

![alt text](https://github.com/WeiyuanW/Covid-Markets/blob/master/Tables/COVID%20vs%20Market%20Correlation%20Values%20Table.png?raw=true)

In the next study, we will include more data to exam our hypothesis. We are still in the pandemic, therefore new data and events are becoming available as the overall landscape is ever changing. This future work will analyze pre-, during-, and post- COVID-19 pandemic to built a model of how epidemic disease impact these financial markets.


## Visualizations

         

## Authors
Giovanny Ruiz
Karina Quiroga
Maria del mar Del Valle
Weiyuan Wu
Sean Mondesire, Ph.D   


## Acknowledgments
The original research summarized in the following was supported, in part, by U.S. Department of Education grant award P031C160161 (STEM SPACE).  Any opinions, findings, and conclusions or recommendations expressed in this material are those of the authors and do not necessarily reflect the views of the funding agency.

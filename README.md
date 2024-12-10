# IE 534 - Deep Dive Project
# 
Group 31
Project 7

## Team members
Noel Mrowiec (mrowiec3@illinois.edu)  
Hanliang Jiang (hj33@illinois.edu)  
Hong-Ming Chiu (hmchiu2@illinois.edu)  

## Overview
This is the final project for IE 534 / CS 547 Deep Learning at the UIUC. The final project is known as a deep dive project. 

## Problem Statement
For this project, we will be predicting the price of energy provided by MISO (Midcontinent Independent System Operator). We are given different features, including Forecasted Load, Day Ahead Energy Price, Time, Energy prices in surrounding states and Predicted weather, and will be using recurrent neural networks to predict the price. The label (actual energy price) is the ground truth. We will try to predict the label.  

Label: 
-Actual Energy Price (http://www.energyonline.com/Data/GenericData.aspx?DataId=8&MISO___Actual_Energy_Price) for ILLINOIS.HUB

Features: 
-Forecasted Load 
-Day Ahead Energy Price 
-Day of Week 
-Hour of Day 
-Month 
-Energy prices in surrounding states 
-Daily temperature 


## Data
The data for this project is from various sources. 

- Forecasted Load, Day Ahead Energy Price, Energy prices in surrounding states and the corresponding dates all comes from http://www.energyonline.com/Data
- The temperature reading comes from https://www.sciencebase.gov/catalog/item/660ad9d2d34e4df16bd58a23


## Features

We will use the following column in the dataset as feature:

Sin_Month, Cos_Month. Month in cyclical data format.
Sin_Day, Cos_Day. Day of the week in cyclical data format.
Sin_Hour, Cos_Hour. Hour of the day in cyclical data format.
Temperature. Air temperature at Illinois.
Forecasted Load (MISO). Forecasted Load from MISO.
Day Ahead Energy Price (IL). Day Ahead Energy Price at Illinois.
Energy Price (MICHIGAN.HUB). Energy Price at Michigan hub.
Energy Price (INDIANA.HUB). Energy Price at Indiana hub.
Energy Price (ARKANSAS.HUB). Energy Price at Arkansas hub.


Milestone 1: 

Milestone 2:

Milestone 3:

Milestone 4:

Milestone 5:

Conclusions:




## MIT License


Copyright (c) 2019-2024 
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




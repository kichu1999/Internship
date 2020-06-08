# Internship
## Financial Market Analysis


This project was completed as a part of Career Launcher machine learning internship. 

 ### **1. Data processing and analysing**
  a. Imported csv file of stock\
  b. To avoid repetitions in the date all rows where 'Series' colum not 'EQ' was deleted.\
  c. Calculated maximum, minimum and mean prices for the last 90 days\
  d. Analysed data types of each column\
  e. To make use of Pandas functionality, converted 'Date' column from 'object' to 'datetime64(ns)'.\
  f. Calculated monthwise VWAP(Volume Weighted Average Price).\
  g. Defined a function to calculate the average price over the last n days.\
  h. New column('Day_Perc_Change') created with the daily percentage change of price.\
  i. New column 'Trend' added based on the range of values of 'Day_Perc_Change'.\
  j. Calculated average and median values of the column 'Total traded Quantity' for each of the types of 'Trend'.
  
### **2. Data visualization and Technical Analysis**
  a. Plotted the closing price of each day.\
  b. Compared the stem plots of percentage change of the price and daily volumes.\
  c. Plotted a pie chart with each sector representing the percentage of days each trend occurs.\
  d. Created a bar plot of average and median values of the 'Total Traded Quantity'.\
  e. Plotted percentage daily return as a histogram.\
  f. Analysed correlation of different stocks.\
  g. Calculated and plotted Rolling Change in Average and Variance of Percentage Change of stock price.\
  h. Compared the volatility of Nifty index with the given index.\
  i. Trade Calls made based on simple moving avrages.\
  j. Plotted Bolinger bands of the stock.
  
### **3. Fundamental Analysis using Regression**
  a. Calculated Beta value using regression.
  
### **4. Trade call prediction using classification**
  a. Trade Calls made using Bolinger bands.\
  b. Utilized classification to make trade calls for the stock.\
  c. Used already defined classification model to make trade calls for a new stock.\
  d. Made trade calls by adding new features and training a new classification model.
  
### **5.Modern Portfolio Theory**
  a.Chose 5 different stocks of different caps.\
  b.Calculated annual returns and volatility of th entire portfolio assuming equal weightage.\
  c.Providing different weights for individual stocks, calculated returns and volatility of the portflio.\
  d.Prepared a scatter plot of the same.\
  e.Marked points of highest Sharpe ratio and lowest volatility.
  
### **6. Clustering for Diversification Analysis**
  a. Created a dataframe with the closing prices of 30 different stocks, with 10 from each of the stacks.\
  b. Calculated annual percentage return and volatility over one year period\
  c. Clustered them according to mean annual Volatilities and Returns using K-means clustering.\
  d. Identified optimum number of clusters using Elbow curve method.\
  e. Plotted different clusters. 


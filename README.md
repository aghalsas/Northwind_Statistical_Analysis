
# Module 3 -  Final Project Specifications

## Introduction

This is a fake dataset of the Northwind trading company. The data is in a SQL database that we query to get the information we need

# Objectives

The following are the questions we answer in this project by using hypothesis testing

## Summary and Conclusions

## Q1 Does discount amount have a statistically significant effect on the quantity of a product in an order? If so, at what level(s) of discount?
 - Considering all products discounted items are drawn from a different distribution compared to undiscounted items at the 95% confidence level
 - Considering individual discount levels, discounted products at 0.05, 0.15, 0.2, and 0.25 levels are drawn from a a different distribution compared to the undiscounted quantities and have higher means. There is no concrete distinction in the distributions between 0.05, 0.15, 0.2 and 0.25 levels. 0.1 discount level needs to have more data points for us to potentially reject the null hypothesis
 - At the individual product level there is no evidence that discount levels matter, However that is most likely due to low statistics per product and per discount level.
 
## Q2 Do sales get drawn from a different distribution every year? Does the month when the products were ordered matter? 
 - The sales do not seem to depend on year and the quantities seem to be drawn from the same underlying distribution. Individual products also don't suggest a preferred year
 - For overall sales the month of May shows a definite decrease in quantities purchased


## Q3 Is there a standout employee in terms of the distribution from which quantities sold are drawn ? Are there employees who are shipping their orders significantly late?
 - There is insufficient evidence that the quantities sold between employees come from different distributions
 - Employees 2,4,7,9 statistically have a bad record of shipping on time compared to Employee 5

## Q4 Are there regions that are growing or decreasing in overall sales ? Are there products that are growing or decreasing in overall sales
 - All regions show a growth comparing year 2012 and 2014
 - All products show a growth comparing year 2012 and 2014


## Blog

https://aghalsasi-datascience.blogspot.com/2020/01/northwind-dataset-statistical-analysis.html
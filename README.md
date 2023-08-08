# Online-Shoppers-Purchasing-Intention-dataset
A simple analysis of the Online Shoppers Purchasing Intention dataset to underline the limits of applying a simplistic approach. This is the homework assigned at the end of the course of Machine Learning. 
## General Info
Dataset: Online Shoppers Purchasing Intention dataset
Aim: build a classification model that can predict whether or not an online shopper has
the intention to make a purchase
## Dataset composition
Type of variable: 
- Categorical → information on the type of the operating system, the region of the shopper, and whether or not the shopper was a returning visitor
- Continuous → information on the duration of the visit, the number of pages visited, and the exit rate, among others.
Dataset attributes: 
- *Administrative:* number of pages of the website related to the administrative section that the user visited
- *Administrative Duration:* total time spent by the user on the website's administrative pages
- *Informational:* number of pages of the website related to the informational section that the user visited
- *Informational Duration:* total time spent by the user on the website's informational pages
- *Product Related:* number of pages of the website related to the product that the user visited
- *Product Related Duration:* total time spent by the user on the website's product pages.
- *Bounce Rate:* percentage of visitors who enter the website and leave without viewing any other pages during that session.
- *Exit Rate:* percentage of visitors who leave the website from that page during that session
- *Page Value:* average value of the page that the user visited before landing on the goal page during that session
- *Special Day:* closeness of the visit to a special day such as Mother's Day or Valentine's day.
- *Month:* month of the year in which the visit took place
- *Operating System:* type of operating system used by the user
- *Browser:* type of browser used by the user.
- *Region:* region of the user
- *Traffic Type:* type of traffic through which the user reached the website.
- *Visitor Type:* type of visitor, i.e., new or returning.
- *Weekend:* categorical feature representing whether the visit took place on a weekend or not.
- *Revenue:* This is the target variable, a binary feature that indicates whether the visitor made a purchase or not

**NOTE** -> the dataset is divided in training and test. In both dataset there is a significant dataloss of the Exit Rate variable, so it's necessary to recover them.

## Project steps
### 1. Preliminary analysis 
- Visualizing samples
- Identifying if features are correlated
- Determining which are most correlated with the target class
- Inspecting the distribution of samples among classes
- Recovering the data loss for ExitRates
### 2. Classification
Build a **classification model** to correctly predict if an online shopper is likely to perform a purchase:
- Perform features selection
- Compare different algorithms
- Identify the one that works the best on this dataset
- Finally, test the performance of the best algorithm on the provided test set.
Determine whether a model built using the Exit Rate information is better than a model built using the remaining features.
### 3. Clustering 
Repeat the analysis done at step 2 with clustering based algorithms; compare the performance with respect to the best classification model.

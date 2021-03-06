# AB-test
### Udacity Data Analyst Nanodegree
### Project III: Analyze A/B Test Results
### Table of contents
* [Setup](#setup)
* [Project Overview](#Project)
* [Part I - Probability](#Probability)
* [Part II - A/B Test](#A/B Test)
* [Part III - Regression](#Regression)
* [Results](#Results)

## Setup
The project is created on Jupyter Notebook. The following packages are installed. These packages can be installed via conda or pip.
Numpy
Pandas
Matplotlib
Statsmodels
Scipy

## Project Overview - Analyze A/B Test Results
A/B tests are very commonly performed by data analysts and data scientists.

For this project, I was working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. My goal was to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

The dataset  reflecting data collected from an experiment is provided. The statistical techniques to answer questions about the data and to report 
conclusions are used.
##Part I - Probability
Statistics were computed to find out the probabilities of converting regardless of page. These were used to analyze if one page or the other led to more conversions.

## Part II - A/B Test
The A/B testing was conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

Part III - Regression
Logistic regression was then performed to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

## Results
Based on the statistical tests I used, the Z-test, logistic regression model, and actual difference observed, the results have shown that the new and old page have an approximately equal chance of converting users. We fail to reject the null hypothesis. Overall there is not enough evidence on deciding to switch to the new page rather than stay with the old one so I recommend to the e-commerce company to keep the old page.

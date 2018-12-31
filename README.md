# Create a Customer Segmentation Report for Arvato Financial Solutions
---

## Introduction
In this project, I work with real-life data provided to us by Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. 

I applied unsupervised learning techniques on demographic and spending data for a sample of German households. I also pre-processed the data, apply dimensionality reduction techniques, and implement clustering algorithms to segment customers with the goal of optimizing customer outreach for a mail order company. 

Besides that, I also have access to a third dataset with attributes from targets of a mail order campaign. A supervised machine learning model was setup to predicts whether or not each individual will respond to the campaign.

---

## Installation

The following python tools/module packages is needed for this study.

- python 3.6
- anaconda
- jupyter notebook
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

---

## Motivation/Object of project

Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. 

The general population into clusters were organized by using unsupervised learning techniques , then use those clusters to see which of them comprise the main user base for the company. After knowing which parts of the population are more likely to be customers of the mail-order company, I also build supervised machine learning model to to decide whether or not it will be worth it to include that person in the campaign, by using the demographic information from each individual.

---

## Files Uploaded in Repository

The following are all file/data that needed for this project.
- Jupyter Notebook (Arvato Project Workbook.ipynb) - codings for each steps of CRISP-DM (Cross Industry Process for Data Mining)
- CSV file for Kaggle Competition (csvFile_KaggleCompetition.csv) - csv file prepared for Kaggle Competition

---

## Summary of the results of the analysis

In this project, we could make the following conclusion based on the results predicted from the supervised and unsupervised models which were fitted and predicted based on the 4 datasets provided by Bertelsmann partners AZ Direct and Arvato Finance Solution.

1. By using the clustering model (unsupervised model learning), the people groups which are overrepresented in the customer data compared to the general population have the following background information:

- higher activity of the last transaction with the complete file TOTAL
- higher activity of the last transaction for the segment mail-order TOTAL
- higher transaction activity TOTAL POOL in the last 24 months
- higher transaction activity TOTAL POOL in the last 12 months

2. Whereas, the people groups which are underrepresented in the customer data compared to the general population have the following background information:

- lower number of 1–2 family houses
- lower share of car owners
- higher number of cars
- higher share of cars built

3. By using the supervised model prediction (ADABOOST classifier), all predicted results shows no responses from all individual.

For more information of this analysis project, you could refer to my Medium Blog Post at [HERE](https://medium.com/p/99b1954dfd58)

---
## Acknowledgement

I couldn’t have finish this project without the help of a lot of people. I’d like to thank the Udacity instructors and the rest of the Udacity staff for their invaluable help. Thanks to my project mentors, for great suggestions, edits, and support.


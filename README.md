# BCG - Data Science Job Simulation on Forage

---

This repo details the work that I did for BCG's data science job simulation on Forage. This simulation consisted of six different tasks:
1. **Task One -** Introduction to the customer churn problem
2. **Task Two -** Constructing an email to PowerCo (gas & electric provider that served as our client for this simulation) inquiring about the data we need and techniques we'll use to solve the problem
3. **Task Three -** Exploratory data analysis
4. **Task Four -** Feature engineering
5. **Task Five -** Modeling the data
6. **Task Six -** Creating an executive summary slide with our insights and actions that could be used to solve the churn problem

---

### TASK ONE - INTRODUCTION

​In this simulation, you’ll be working with a case team to help a client, PowerCo, investigate a problem with customer churn. PowerCo suspects price sensitivity is driving their customers to switch providers—the data tells a more complex story. Your job is to dig into the data, develop hypotheses, build predictive models, and translate your insights into strategic recommendations.

This experience reflects the real work our teams do every day:

* Framing business problems through a data science lens

* Analyzing and cleaning real-world datasets

* Engineering features that drive better predictions

* Building and evaluating models using tools like Python

---

### TASK TWO - EMAIL

While you were reviewing the case materials, your team held a team meeting to discuss the client brief and generate hypotheses about the cause. 

During the meeting the someone on your team noted that the client strongly believes that the for churn (among others) is that customers have become more “sensitive” to the price and are opting toward low-cost providers – we need to test this hypothesis.

You will partner with Estelle, a senior data scientist, to uncover the insights we need to validate or disprove the idea that price is the critical factor.

You and Estelle know that the first step in any case is to understand the business and frame the problem – we need the right data points and techniques to do that.

To ensure we can successfully identify the cause, your task is to draft an email clearly outlining the data that we’ll need from the client and the techniques you will use to investigate the issue.

To help get you started, ask yourself:
* What are all of the possible reasons a customer would choose to stay with or switch energy providers? (for example: price, energy source, customer service, etc.)
* What data points would be needed in order to effectively analyze causes of churn? (e.g. purchasing trends, location of business etc.)
* Once we have the data, what steps will you take to process and analyze the information? (hint: use the 5-step process outlined below)

BCG X is transforming businesses using data science to help companies generate competitive advantage. To do this, we typically follow a 5-step methodology:
1. Business understanding & problem framing: what is the context of this problem and why are they trying to solve it?
2. Exploratory data analysis & data cleaning: what data are we working with, what does it look like and how can we make it better?
3. Feature engineering: can we enrich this dataset using our own expertise or third party information?
4. Modeling and evaluation: can we use this dataset to accurately make predictions? If so, are they reliable?
5. Insights & Recommendations: how we can communicate the value of these predictions by explaining them in a way that matters to the business?

Communicating your findings in a clear, actionable way.

The link to this task can be found [here.](https://github.com/regmckie/BCG_Data-Science_Job-Simulation/blob/main/Task2_Email.txt)

---

### TASK THREE - EXPLORATORY DATA ANALYSIS

As a Data Scientist at BCG, there will be occasions when you need to analyze data or investigate an issue but you may not have been given provided strict instructions or guidance.

It is a highly valuable skill to learn how to investigate a problem independently – a great way to start is to build a framework for analysis that works for you.

​Through exploratory data analysis (EDA) a Data Scientist uses statistical techniques like descriptive statistics and visualizations to gain a deeper understanding of the statistical properties that the data holds

In this step, you'll need to analyze client data sets using Python and upload your work as a Jupyter notebook.

The three (3) data sets provided by the client are:
* Historical customer data: Customer data such as usage, sign up date, forecasted usage etc.
* Historical pricing data: variable and fixed pricing data at different points in time
* Churn indicator: whether each customer has churned or not

You need to analyze the following using Python:
* The data types of each column
* Distributions of columns

The link to this task can be found [here.](https://github.com/regmckie/BCG_Data-Science_Job-Simulation/blob/main/Task3_EDA.ipynb)

---

### TASK FOUR - FEATURE ENGINEERING

Your task is to create new features for your analysis and upload your completed python file. 

As before, a good way to quickly learn how to effectively feature engineer is to build a framework to follow. Below is an example of how you could attempt this task:

*First -* can we remove any of the columns in the datasets?
* There will almost always be columns in a dataset that can be removed, perhaps because they are not relevant to the analysis, have only have 1 unique value, or are nearly identical to another column.

*Second -* can we expand the datasets and use existing columns to create new features?
* For example, if you have “date” columns, in their raw form they are not so useful. But if you were to extract month, day of month, day of year and year into individual columns, these could be more useful.

*Third -* can we combine some columns together to create “better” columns?
* How do we define a “better” column and how do we know which columns to combine?
* We’re trying to accurately predict churn - so a “better” column could be a column that improves the accuracy of the model.
* And which columns to combine? This can sometimes be a matter of experimenting until you find something useful.

*Finally -* can we combine these datasets and if so, how?
* To combine datasets, you need a column that features in both datasets that share the same values to join them on.

At this stage, your data could look vastly different or may have just some subtle differences to how it was before.

You will be done with this task when you’re happy with the new set of features that you’ve created and you think you’re ready to build a model to see which of these features are useful for predicting churn. 

The link to this task can be found [here.](https://github.com/regmckie/BCG_Data-Science_Job-Simulation/blob/main/Task4_FeatureEngineering.ipynb)

---

### TASK FIVE - MODELING THE DATA

After the previous task of feature engineering, Estelle conducted a further review and has provided you with a final dataset to use for this task, named “data_for_predictions.csv”. Be sure to use this dataset for this task.

To best predict the customer churn, your task is to:
* Train a random forest classifier to predict churn
* Evaluate the predictions using metrics to demonstrate how accurately the model has performed

The link to this task can be found [here.](https://github.com/regmckie/BCG_Data-Science_Job-Simulation/blob/main/Task5_ModelingExample.ipynb)

---

### TASK SIX - EXECUTIVE SUMMARY SLIDE

Develop an abstract slide synthesizing all the findings from the project, keeping in mind that this will be for the key stakeholders meeting which the Head of the SME division (as well as other various stakeholders) will be attending.

Note: a steering committee meeting is a meeting where the BCG team presents key findings and recommendations (and/or project progress) to key client stakeholders.

A few things to think about for this abstract include:
* What is the most important number or metric to share with the client?
* What are the next steps the client should take following your analysis?
* What business impact? How would the model affect the client’s bottom line?

The link to this task can be found [here.](https://github.com/regmckie/BCG_Data-Science_Job-Simulation/blob/main/Task6_ExecutiveSummary.pdf)

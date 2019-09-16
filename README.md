# Data Analysis Interview Challenge

This is your chance to show us with creative and rigorous solutions! Please include your code at the end of your submission, or in a separate file. We also accept incomplete solutions.

## Contents:
 
1. Exploratory data analysis
- The attached logins.json file contains (simulated) timestamps of user logins in a particular geographic location. Aggregate these login counts based on 15 minute time intervals, and visualize and describe the resulting time series of login counts in ways that best characterize the underlying patterns of the demand. Please report/illustrate important features of the demand, such as daily cycles. If there are data quality issues, please report them. Analysis in [`data_challenge_part1`](./data_challenge_part1.ipynb)

2. Experiment and metrics design
- The neighboring cities of Gotham and Metropolis have complementary circadian rhythms: on weekdays, Ultimate Gotham is most active at night and Ultimate Metropolis is most active during the day. On weekends, there is a reasonable activity in both cities.

- However, a toll bridge, with a two-way toll, the two cities causes driver partners to tend to be exclusive to each city. The Ultimate managers of city operations for the two cities have proposed and experiment to encourage driver partners to be available in both cities, by reimbursing all toll costs.

- What would you choose as the key measure of sucess of this experiment in encouraging driver partners to serve both cities, and why would you choose this metrics?

- Describe a practical experiment you would design to compare the effectiveness of the proposed change in relation to the key measure of success. Available in [`data_challenge_part2`](./data_challenge_part2.ipynb)

3. Predictive Modeling
- Ultimate is interested in predicting rider retention. To help explore this question, we have provided a sample dataset of a cohort of users who signed up for an Ultimate account in January 2014. The data was pulled several months later; we consider a user retained if they were “active” (i.e. took a trip) in the preceding 30 days. We would like you to use this data set to help understand what factors are the best predictors for retention, and offer suggestions to operationalize those insights to help Ultimate. The data is in the attached file ultimate_data_challenge.json. See below for a detailed description of the dataset. Please include any code you wrote for the analysis and delete the dataset when you have finished with the challenge.

 - Perform any cleaning, exploratory analysis, and/or visualizations to use the provided data for this analysis (a few sentences/plots describing your approach will suffice). What fraction of the observed users were retained?
 - Build a predictive model to help Ultimate determine whether or not a user will be active in their 6th month on the system. Discuss why you chose your approach, what alternatives you considered, and any concerns you have. How valid is your model? Include any key indicators of model performance.
 - Briefly discuss how Ultimate might leverage the insights gained from the model to improve its long term rider retention (again, a few sentences will suffice). Analysis in 
 [`data_challenge_part3`](./data_challenge_part3.ipynb)


## Getting Started

### Prerequisites

- [Download Anaconda](https://www.anaconda.com/distribution/).
- Run Anaconda Navigator and launch a jupyter notebook and open the files listed below.
- Using Anaconda Navigator, you can install the package py-xgboost

Packages applied in this project (numpy, scipy, matplotlib, pandas, seaborn, sklearn, datetime, json) do not require installation (default packages in anaconda). They only need to be imported in the notebook. 
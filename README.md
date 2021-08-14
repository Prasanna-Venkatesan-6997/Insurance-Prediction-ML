# Insurance-Prediction-ML

An insurance company has been providing health insurance to its customers and are now hoping to build a model to predict whether the policy holders from past will also be interested in Vehicle Insurance provied by the company.

Building this model would help the company so that it can be used to plan its communcation strategy to reach out to those customers and optimise its business model and revenue.

Now, in order to predict, whether the customer would be interested in Vehicle Insurance, the following information are at hand in the dataset,

1. id
2. Gender
3. Age
4. Driving_License - 0 : Customer does not have DL, 1 : Customer already has DL
5. Region_Code
6. Previously_Insured - 1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance
7. Vehicle_Age
8. Vehicle_Damage - 1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past
9. Annual_Premium - The amount customer needs to pay as premium in the year
10. PolicySalesChannel - Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.
11. Vintage - Number of Days, Customer has been associated with the company
12. Response - 1 : Customer is interested, 0 : Customer is not interested

Descriptive analytics and statistics on the dataset is produced along with data preprocessing steps in datavisualisation-preprocessing.ipynb and prediction is done in predictivemodels.ipynb.

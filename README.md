# CreditCard-Approval

Author: KRIT PATEL 

### Business problem:

Creating a prediction model that approves credit cards to applicants.


### Data:
Data From : https://www.kaggle.com/datasets/samuelcortinhas/credit-card-approval-clean-data?select=clean_dataset.csv

Data set: https://drive.google.com/file/d/1YVNqAidPyIM--ESYi4J7q0uuy2sN7iQd/view?usp=drivesdk

## Methods

Data Cleaning: 

The dataset had been cleaned before hand and had no duplicated or missing values.
All ordinal data was already Ordinaly Encoded.


Feature and Target Selection:

Since the objective of this model is to predict for approval, the 'Approved' column was set as the target

Columns regarding 'Gender' , 'Ethnicity', 'Citizen', 'Industry', and 'ZipCode' were eliminated from the feature column.

Preprocessing:

The data is preprocessed using various pipelines

Models Implemented:

1. Logistical Regression Model

   Model 1: Untuned model
   Model 2: Tuned model
   Model 3: PCA applied to the Tuned model
   
2. Random Forest

   Model 1: Untuned model
   Model 2: Tuned model
   Model 3: PCA applied to the Tuned model
   
3. K Nearest Neighbor
   
   Model 1: Untuned model
   Model 2: Tuned model
   Model 3: PCA applied to the Tuned model
   
Results: Tuned Random Forest provides the best accuracy with minimum variance between the training and testing accuracy scores. 

## Visualization

![image](https://user-images.githubusercontent.com/103543062/176869800-b597ca2e-c133-4066-82a4-b5ef283f7f88.png)


This graph indicates that all applicants with an income of more than $ 1000 got approved regarless of whether or not they have defaulted on a payment in the past.

![image](https://user-images.githubusercontent.com/103543062/176869880-4005a9de-4e64-4897-9c9c-d50aa394630b.png)

This barchart indicates that applicants with a prior default who are employed are more likely to get approved for a credit card. It also indicates that for those who do not have a prior default,however small the sample may be, the applicants that are not employeed are more likely to get approved for a credit card.

![image](https://user-images.githubusercontent.com/103543062/176869942-0c3bd5cf-e8c7-4878-8645-4c5200826443.png)

This line graph indicates that applicants who have a prior default, the higher the debt, the more likey they are to get approved, while as for the applicants that do not have a prior default, the lower the debt, the  higher the chances are for their approval.





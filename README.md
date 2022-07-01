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

![D49F0B35-E40B-47D4-8A2F-EA63FE41564F](https://user-images.githubusercontent.com/103543062/176866872-2f2e41c7-4ef7-4de3-8e33-7c6164cad492.png)

This graph indicates that all applicants with an income of more than $ 1000 got approved regarless of whether or not they have defaulted on a payment in the past.

![1E1E9B54-04D5-4746-B712-2B6844457997](https://user-images.githubusercontent.com/103543062/176866913-d3eb907c-4615-4ef4-abee-32453be467be.png)

This barchart indicates that applicants with a prior default who are employed are more likely to get approved for a credit card. It also indicates that for those who do not have a prior default,however small the sample may be, the applicants that are not employeed are more likely to get approved for a credit card.

![00711853-9395-4731-A5F4-C8673E130D8A](https://user-images.githubusercontent.com/103543062/176866964-f7dd1c93-72e3-4178-ae0f-f4d30402ba74.png)

This line graph indicates that applicants who have a prior default, the higher the debt, the more likey they are to get approved, while as for the applicants that do not have a prior default, the lower the debt, the  higher the chances are for their approval.





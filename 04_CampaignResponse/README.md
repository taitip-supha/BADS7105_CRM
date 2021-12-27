## Campaign Response
We use Retail_Data_Response (customer level) and Retail_Data_Transactions (transactions level) for prediction customer response.

## Retail_Data_Response
![df_response](./img00_df_response.png)

## Retail_Data_Transactions
![df_transaction](./img01_df_transaction.png)

## Data for training model
We create a feature at customer level from Retail_Data_Transactions and then join with Retail_Data_Response
![df_modeling](./img02_df_final.png)

## Fix imbalanced data with Oversampling (SMOTE)
![Oversampling](./img03_oversampling.png)

## Logistic Regression
![Oversampling](./img04_LogisticReg.png)

## XGBoost
![Oversampling](./img05_XGBoost.png)
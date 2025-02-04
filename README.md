# CustomersSegmentation_FinancialMarketingCampaings
Customer Segmentation based on financial behaviours to set targeted marketing campaigns

Customer segmentation for targeted marketing campaigns.  
This segmentation will allow the company to target personalized marketing campaigns to each customer cluster, thus maximizing the return on investment and improving the user experience.
The main objective is to develop a customer segmentation model based on the information provided by the company dataset in which spending and credit card usage behaviors are recorded.
Dataset Description:  
• CUST_ID: Unique identifier of the credit card holder (categorical).  
• BALANCE: Amount of the balance remaining on the account for purchases.  
• BALANCE_FREQUENCY: Frequency of updating the balance, with a score between 0 and 1 (1 = frequently updated, 0 = not frequently updated).  
• PURCHASES: Total amount of purchases made from the account.  
• ONEOFF_PURCHASES: Maximum amount of purchases made in a single solution.  
• INSTALLMENTS_PURCHASES: Amount of purchases made in installments.  
• CASH_ADVANCE: Cash advance given by the user.  
• PURCHASES_FREQUENCY: Frequency of purchases, with a score between 0 and 1 (1 = frequent purchases, 0 = infrequent purchases).  
• ONEOFF_PURCHASES_FREQUENCY: Frequency of one-off purchases (1 = frequent, 0 = infrequent).  
• PURCHASES_INSTALLMENTS_FREQUENCY: Frequency of installment purchases (1 = frequent, 0 = infrequent).  
• CASH_ADVANCE_FREQUENCY: Frequency of cash advance requests.  
• CASH_ADVANCE_TRX: Number of cash advance transactions made.  
• PURCHASES_TRX: Total number of purchase transactions made.  
• CREDIT_LIMIT: Maximum credit card limit for each user.  
• PAYMENTS: Total amount of payments made by the user.  
• MINIMUM_PAYMENTS: Minimum amount of payments made by the user.  
• PRC_FULL_PAYMENT: Percentage of full payment paid by the user.  
• TENURE: Duration of credit card service for the user (in years).  

Project Phases
1. Exploratory Data Analysis (EDA)  
to better understand the distribution of the variables, identify any missing data and evaluate the need for data transformations.  
2. Data Preprocessing  
• Handling of missing values ​​(for variables such as MINIMUM_PAYMENTS).  
• Normalization and standardization of quantitative variables.  
3. PCA to visualize the data in a compact way  
• with 2 and 3 principal components, this allows to visualize samples paterns.  
4. Segmentation through Clustering  
• Use of clustering algorithms with K-Means to identify groups of homogeneous customers.  
• Evaluation of clustering performance through the Elbow method.  
5. Interpretation of Clusters  
Analysis and description of the different clusters in terms of: - Average expenses (balance sheet, lump sum purchases, installment purchases). - Payment habits (percentage of minimum payments, full payments). - Frequency of card use (cash advances, purchase frequency).  

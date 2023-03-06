# Credit Card Analysis With Clustering

Credit card clustering means grouping credit card holders based on their buying habits, credit limits, and many more financial factors. It is also known as credit card segmentation. Such clustering analysis helps businesses find their potential customers and many more marketing strategies.

To do the analysis I needed a dataset with a set of data based on a person's credit card purchase history. You can see the dataset in `kaggle datasets download -d arjunbhasin2013/ccdata`. 

## Below are all the features in the dataset:

* CUST_ID: Unique identification number of the customer
* BALANCE: Balance in the bank account of the customer
* BALANCE_FREQUENCY: How frequently the balance is updated in the account of * the customer (1 means frequently updated, and 0 means not frequently updated)
* PURCHASES: The number of purchases made by the customer
* ONEOFF_PURCHASES: Maximum amount of one-time purchase
* INSTALLMENTS_PURCHASES: Amount of purchases on instalments
* CASH_ADVANCE: Cash in advance paid by the customer
* PURCHASES_FREQUENCY: The frequency of purchases (1 means high frequency, 0 means low frequency)
* ONEOFF_PURCHASES_FREQUENCY: The frequency of one-time payment purchases (1 means high frequency, 0 means low frequency)
* PURCHASES_INSTALLMENTS_FREQUENCY: The frequency of purchases on instalments (1 means high frequency, 0 means low frequency)
* CASH_ADVANCE_FREQUENCY: Frequency of cash in advance payments
* CASH_ADVANCE_TRX: Number of cash in advance transactions
* PURCHASES_TRX: Number of transactions on purchases
* CREDIT_LIMIT: Credit limit of the customer
* PAYMENTS: Amount of payments made by the customer
* MINIMUM_PAYMENTS: Amount of minimum payments made by the customer
* PRC_FULL_PAYMENT: Percentage of full payment made by the customer
* TENURE: The tenure of the credit card service of the customer

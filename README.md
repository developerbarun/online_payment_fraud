Here I have tried to solve online fraud issue with the help of machine learning in Python.

The dataset we will be using have these columns – 

|__________________________________________________________________________|                                                                                                 
|Feature    	   |     Description                                         |                                                                                                 
|_________________________________________________________________________ |
| step	         |   tells about the unit of time                          |
| type	         |   type of transaction done                              |
| amount	       |   the total amount of transaction                       |
| nameOrg	       |   account that starts the transaction                   |
| oldbalanceOrg	 |   Balance of the account of sender before transaction   |
| newbalanceOrg	 |   Balance of the account of sender after transaction    |
| nameDest	     |   account that receives the transaction                 |
| oldbalanceDest |   Balance of the account of receiver before transaction |
| newbalanceDest |   Balance of the account of receiver after transaction  |
| isFraud	       |   The value to be predicted i.e. 0 or 1                 |
|__________________________________________________________________________|

Libraries used
1. Pandas
2. Seaborn/Matplotlib
3. Numpy
4. sklearn 

Here I have tried to solve online fraud issue with the help of machine learning in Python.

The dataset we will be using have these columns – 

   |__________________________________________________________________________|                       
   |Feature    	   |     Description                                         |                             
   |_________________________________________________________________________ |                                              
1.   | step	         |   tells about the unit of time                          |                                             
2.   | type	         |   type of transaction done                              |                                            
3.   | amount	       |   the total amount of transaction                       |                                             
4.   | nameOrg	       |   account that starts the transaction                   |                                           
5.   | oldbalanceOrg	 |   Balance of the account of sender before transaction   |                                          
6.   | newbalanceOrg	 |   Balance of the account of sender after transaction    |                                           
7.   | nameDest	     |   account that receives the transaction                 |                                            
8.   | oldbalanceDest |   Balance of the account of receiver before transaction |                                            
9.   | newbalanceDest |   Balance of the account of receiver after transaction  |                                            
10.  | isFraud	       |   The value to be predicted i.e. 0 or 1                 |                                           
  |__________________________________________________________________________|                                               

Libraries used
1. Pandas
2. Seaborn/Matplotlib
3. Numpy
4. sklearn 

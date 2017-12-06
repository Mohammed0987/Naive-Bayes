# Naive-Bayes

Given a data science table, where each column has valid comparable values, the function returns a conditional table or an accuracy of the method for the respective tables. 

conditional(chosen, table) produces the conditional tables. The chosen table is the variable by which the rest of the variables will be estimated by. Table is the training set to determine the conditional tables.

accuracy(a, table, chosen) produces the accuracy from the conditional table applying the chosen and testing the preictions against the tables chosen column. a represents the conditional tables which comes as a dictionary. table represents the data that a will be tested on. chosen represents the variable which needs to be predicted. 

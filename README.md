# Mercedes-Benz-Greener-Manufacturing

Problem 
Since the first automobile, the Benz Patent Motor Car in 1886, Mercedes-Benz has stood for important automotive innovations. These include the passenger safety cell with a crumple zone, the airbag, and intelligent assistance systems. Mercedes-Benz applies for nearly 2000 patents per year, making the brand the European leader among premium carmakers. Mercedes-Benz is the leader in the premium car industry. With a huge selection of features and options, customers can choose the customized Mercedes-Benz of their dreams.
To ensure the safety and reliability of every unique car configuration before they hit the road, the company’s engineers have developed a robust testing system. As one of the world’s biggest manufacturers of premium cars, safety and efficiency are paramount on Mercedes-Benz’s production lines. However, optimizing the speed of their testing system for many possible feature combinations is complex and time-consuming without a powerful algorithmic approach.
You are required to reduce the time that cars spend on the test bench. Others will work with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Mercedes-Benz’s standards.

Objective
Reduce the time a Mercedes-Benz spends on the test bench.

Datasets 
Train.csv (For Training the model)
Test.csv (For Model Deployment)

Actions Performed
Step 1 : Import the required Libraries
Step 2 : Loading the test and train sets
•	Print few rows and see how data looks like.
•	Understanding the data using info()
Step 3 : Deleting the variables with Variance = 0 in Both Train and test sets.
Step 4 : Check for Null  Values for Train and Test set and Deleting them.
Step 5 : Applying Label Encoder To categorical Values.
Step 6 : Reducing the dimensionality of Train Dataset to 120.
Step 7 : Building a model using XGBRegressor.
Step 8 : Training the model using Train Dataset.
Step 9 : Reducing the Dimensionality of Test Data.
Step 10 : Predicting the test_df values using XGBRegressor model trained above.
Step 11: Saving the prediction to csv file Having Columns { ID , Y (prediction) }

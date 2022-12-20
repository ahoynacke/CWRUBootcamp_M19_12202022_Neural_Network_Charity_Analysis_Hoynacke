# CWRUBootcamp_M19_12202022_Neural_Network_Charity_Analysis_Hoynacke

# Project Overview 

Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

# Project Requirements 

- Deliverable 1: Preprocessing Data for a Neural Network Model
- Deliverable 2: Compile, Train, and Evaluate the Model
- Deliverable 3: Optimize the Model

# Deliverable 1: Preprocessing Data for a Neural Network Model 

## The EIN and NAME columns have been dropped

<img width="724" alt="Screenshot 2022-12-20 at 6 22 52 PM" src="https://user-images.githubusercontent.com/111096384/208785728-c5a086c1-1f50-4b5d-b85c-737ea3dfd932.png">

## The columns with more than 10 unique values have been grouped together 

<img width="699" alt="Screenshot 2022-12-20 at 6 23 16 PM" src="https://user-images.githubusercontent.com/111096384/208785770-6c4dd01b-330a-411a-a31a-b5b4a1ea9324.png">

## The categorical variables have been encoded using one-hot encoding 

<img width="698" alt="Screenshot 2022-12-20 at 6 24 15 PM" src="https://user-images.githubusercontent.com/111096384/208785818-faf40582-d074-4e6b-ba14-95d246970cc5.png">

## The preprocessed data is split into features and target arrays 

<img width="694" alt="Screenshot 2022-12-20 at 6 24 34 PM" src="https://user-images.githubusercontent.com/111096384/208785865-c80a137f-47b2-497b-8318-7fc40f9ca7c6.png">

## The preprocessed data is split into training and testing datasets 

<img width="696" alt="Screenshot 2022-12-20 at 6 24 42 PM" src="https://user-images.githubusercontent.com/111096384/208785904-e9e84194-58c6-4b0e-a219-e307fc9c7839.png">

## The numerical values have been standardized using the StandardScaler() module 

<img width="696" alt="Screenshot 2022-12-20 at 6 24 42 PM" src="https://user-images.githubusercontent.com/111096384/208785918-7f3a9095-4b39-431d-a983-3ccb827bd608.png">

# Deliverable 2: Compile, Train, and Evaluate the Model (20 points)

## The number of layers, the number of neurons per layer, and activation function are defined 

<img width="764" alt="Screenshot 2022-12-20 at 6 26 17 PM" src="https://user-images.githubusercontent.com/111096384/208786024-4fb171e7-3023-4df8-aceb-f2bbd3285a0c.png">

## An output layer with an activation function is created 

<img width="1440" alt="Screenshot 2022-12-20 at 6 26 42 PM" src="https://user-images.githubusercontent.com/111096384/208786042-02920e4f-ec53-4214-939c-8cf3578d1099.png">

## There is an output for the structure of the model 

<img width="1440" alt="Screenshot 2022-12-20 at 6 26 42 PM" src="https://user-images.githubusercontent.com/111096384/208786055-110852f1-f637-4ec8-9feb-cf9b85a67067.png">

## There is an output of the model’s loss and accuracy 

<img width="760" alt="Screenshot 2022-12-20 at 6 27 04 PM" src="https://user-images.githubusercontent.com/111096384/208786119-f671f7fc-fe7d-423b-85c2-bfaca148c2bc.png">

## The model's weights are saved every 5 epochs 

<img width="760" alt="Screenshot 2022-12-20 at 6 27 04 PM" src="https://user-images.githubusercontent.com/111096384/208786130-b93b42a2-7876-4c36-ae00-e7e69f8ea44d.png">

## The results are saved to an HDF5 file 

<img width="760" alt="Screenshot 2022-12-20 at 6 27 04 PM" src="https://user-images.githubusercontent.com/111096384/208786137-ef11e99c-3e7b-46e5-b888-0ab38384f8b1.png">

# Deliverable 3: Optimize the Model

- Noisy variables are removed from features 
- Additional neurons are added to hidden layers 
- Additional hidden layers are added 
- The activation function of hidden layers or output layers is changed for optimization 
- The model's weights are saved every 5 epochs 
- The results are saved to an HDF5 file 

<img width="765" alt="Screenshot 2022-12-20 at 6 27 39 PM" src="https://user-images.githubusercontent.com/111096384/208786196-7c972d3d-3b18-4c9d-bb49-770fccb4ec4c.png">

<img width="760" alt="Screenshot 2022-12-20 at 6 27 50 PM" src="https://user-images.githubusercontent.com/111096384/208786236-9b040bfc-e6d1-4353-a783-a192dd891f6a.png">

# Results 

## Data Preprocessing
### What variable(s) are considered the target(s) for your model?
### What variable(s) are considered to be the features for your model?
### What variable(s) are neither targets nor features, and should be removed from the input data?

## Compiling, Training, and Evaluating the Model
### How many neurons, layers, and activation functions did you select for your neural network model, and why?
### Were you able to achieve the target model performance?
### What steps did you take to try and increase model performance?

## Summary 


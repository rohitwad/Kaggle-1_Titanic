# Kaggle-1_Titanic
First Data Science Project on GitHub


<b>Problem Statement: Build a predictive model that answers the question: “what sorts of people were more likely to survive which are on-board on Titanic?” using passenger data (ie name, age, gender, socio-economic class, etc) </b><br/><br/>Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, also known as the “ground truth”.<br/> Test.csv dataset contains similar information but does not disclose the “ground truth” for each passenger. <br/>It’s our job to predict these outcomes. Using the patterns found in the train.csv data, we need to predict whether the other 418 passengers on board (found in test.csv) survived.

Solution : Steps followed to reach the solution

1) Importing Dataset<br/>
2) Cleansing Data <br/>
   a) Handling missing values<br/> 
   &emsp;     i) Deleting column <br/>
   &emsp;    ii) Imputing data <br/>
   b) Handling Categorical Variables<br/>
   c) Creating additional related variables/columns<br/>
   d) Splitting into Train & Testing Set<br/>
   e) Feature Scaling<br/>
4) Building model<br/>
5) Predict<br/>
6) Test model<br/>

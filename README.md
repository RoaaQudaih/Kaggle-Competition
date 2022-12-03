# Kaggle-Competition
##Predict survival on the Titanic.
1.loading data.
  -Read about the dataset and problem.
  -loading train and test data from kaggle using dataframe in pandas library.
2.Analysis Data.
  -Exploratory for the data.  Understanding the data, find the correlation between the columns and find the pattern. 
  -Data Virtualization to find distribution and outliers data.
3. Feature Engineering.
  -The process of manipulating, and transforming raw data into features that can be used in supervised learning.  Filling all missing values (null and NaN) and drop 
  columns that contain NaN values greater than half or not important in training data like ticket.
  -Convert the categorical data to numeric using LabelEncoder.
4.Training the model.
  -After the data is ready and not contain any NaN or null values, and all data is numeric.  Spilt the train data to input and output.
  -Split data to train and test group by using train_test_split function and specify the ratio of test data by test-size.
5.Modeling.
  -Using Machine Learning algorithm for classification inorder to know who passengers is survived or not. 
  -I try many algorithms for accurecy.
6.Testing.
  -Predict on test data.

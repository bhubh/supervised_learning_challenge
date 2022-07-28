# supervised_learning_challenge
In this project, I will create a machine learning model to predict weather a loan will be approved or not for an individual based on his/her finincial features. I will compare the classification accuracy based on prediction from logistic regression and random forest classificier models.
<br>


I use pandas csv reader to read the CSV file and create the dataframe with one of the column represengting classification target data and the rest columns representing data features. The credit approval/disapproval results column was the target of classification. 

<br>
The data was splitted into training and testing data using train-test-split from scikit-learn machine learning algorithms, with 80% of data used as training and rest as test. Additionally, the data was scaled using standardScalar since values in different features differ by order of magnitude. 
<br>
First I used logistic regression model from scikit-learn machine learning algorithms. Which gave pretty good prediction (Training data accuracy score = 0.994 and testing data accuracy score = 0.993). 

<br>
Secondly, I used the random forest classifier model to classify the data which also gave pretty good prediction (Training data accuracy score = 0.998 and testing data accuracy score = 0.992).

<br>
Both the models gave pretty good predition with accuracy higher than 0.99 on testing data though my initial guess was ligistic regression performing better. 

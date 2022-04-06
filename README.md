# AlgerianFireClassification
The data set is timeseries record for forest fires in two different regions in Algeria Bejaia Region Dataset and Sidi-Bel Abbes Region Dataset. The goal of the classifier is to classify the data in order to give a warning before forest fire erupts. Forest fires is considered a major disaster that threatens the earth’s lungs which cause a lot of pollution and lead to multiple loses in resources both natural and human resource
The data set is timeseries record for forest fires in two different regions in Algeria Bejaia Region
Dataset and Sidi-Bel Abbes Region Dataset. The goal of the classifier is to classify the data in
order to give a warning before forest fire erupts. Forest fires is considered a major disaster that
threatens the earth’s lungs which cause a lot of pollution and lead to multiple loses in resources
both natural and human resources. The data set was written in a bad way that I did need to clean it before using it. The header of the
data set wasn’t fixed to the columns so I had to adjusted to have the columns as the header of the
data set. The column’s names had an extra space which I had to fix it by giving new column
name which describes the column’s values without spaces. There was a null value in the data
since the data was divided to two data sets. The data set was poorly written that in index 167
there's an issue in column DC that it contains the column's value and the value of the column
after it so I had to fix this issue also by exploring the error then fixes it. The values of the
“Classes” column was mainly two values “fire” and “not fire” but I was surprised to found out
that I have 9 different values in the column so I had to fix it. I divided the data into two parts one
for each region renamed the “Classes” column’s values 0 for “not fire” and 1 for “fire” for each
part then I did concave those parts to represent a single unified data set. The instances of the data
set were numeric values having a string type so I had to change them to the float type. I then
explored the dataset for double instances and there weren’t any double instances. I explored the
data set for outliers and there was an outlier so I had to standardize the data set. I then explored
the data set for the uniqueness of the “Classes” column values I have discovered that the “Fire” values represent 56.6% of all the values in the “Classes” column while “not fire” represents
43.4%. I then did a lot more discovering for the features of the data for example if rain is greater
or equal to 1 or if the value of FFMC is less than 80. I have used four different models using three different methods which are K Nearest Neighbor, Decision Tree, and Logistic Regression. In order to classify the data set and find out the best
model. For each model I did split the data for 65% for training and 35% for testing then
standardize the features of the data set. I used graphs to give me the best nearest neighbor, solver, metric, and tree depth. The four different models are KNN-8, KNN-2, Decision Tree, and
Logistic Regression. I did build a confusion matrix for each model find out the learning curve
represented the classification report, and the bias, variance, and the mean squared error for each
model. The results of the models were pretty close that KNN-8, KNN-2, and Decision Tree Accuracy on
test set achieved 93.02%, while the Logistic Regression Accuracy on test set has achieved
95.34%. We could see that the KNN method using 8 or 2 and the decision tree method all
reached the testing accuracy of ~93%. But the Logistic Regression had the best results of all
method of reaching a testing accuracy of ~95.3%. All the models achieved same values in
variance, bias, and mean squared error. In conclusion I would like to recommend the usage of Logistic regression for this type of time
series data sets

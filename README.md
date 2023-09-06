# KNN_classifier
Simple KNN_classifier model applied on a classified and unscaled Data.

Introduction:
1. This is just a simple KNN_classifier model applied on a unscaled Data.
2. I did this project in order to test my scaling skills and also create a model to fit the unscaled data.
3. For scaling purposes I have used sklearn library and imported the Scaler module.
4. Also I have used a simple for loop in order to plot the error rate with the number of classifiers that we are using in the model.

Contents:
1. I have used a simple unscaled data in a csv file.
2. Cleaned the data using basic pandas dataframe options.
3. Then scaled the data using the sklearn Scaler model.
4. After scaling, I splitted the data into training and testing segments using the train-test-split model of sklearn.
5. I applied the KNN model for n_neighbours=1 and then calculated my accuracy for this model.
6. The accuracy comes out to be 92%.
7. Now using a for loop i calculated the error rate for different values of numbers of classifiers and plotted against error rate.
8. From the graph, I chose the value 33 as the optimal value of KNN_classifier to give the best accuracy.
9. The optimal accuracy comes out to be 95%.


Conclusion:
I concluded that for an unscaled data scaling is always the most important thing.And after scaling of the data it can be easily fed into any machine learning model.

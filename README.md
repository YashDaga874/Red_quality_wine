# Red_quality_wine
This is basically me working on a random forest regression model on a wine quality dataset that had various input features like free sulphate levels,chlorides etc.and had quality as an output. Hope you like it :)

So firstly here, as usual like we do, I imported the necesary libraries numpy,pandas and matplotlib. Then I proceeded to importing the dataset and separating the features and the labels(quality) and here I applied the condition that was IF quality >=6.5 then its a good quality wine else its not.
Then I proceeded to data preprocessing where in firstly I checked for any null values in the dataset.Then I proceeded to make a few plots between the features and the label to get a hang of how they affected the label y. The correlation heatmap made it even clearer what and how the features were related to the label.

Then it was data splitting into train and test sets and training the Random regressor model with the tree sizes of 100(n_estimators).Then predicted the outcomes on the x_test and using the r2 score we evaluated the model accuracy which came out around 93%. 

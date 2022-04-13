# TorontoPoliceService_BicycleThefts
**Pre-processing:**
1) Some columns in the dataset are dropped because of duplicate info or poor quality.
2) Features such as season, speed tier, and time scope are generated based on related columns.  These features we further use to fine tune and train using the respective model.
3) To evaluate the interpretability of each feature, feature importance and sharply value are adopted. Using different methods to measure is the way to cross compare for a comprehensive and integral evaluation.
4) All plots depicted by feature importance and sharply value indicate weak contributions for season, speed tier, and time scope.
5) To work on the models, we have extracted features and converted our data into binary values based on their type.
6) The co relation between the columns have been explored. However only ‘BikeSpeed’ column has some logical and relatable score. 

# Model Accuracy with different classifier

**KNN (K-nearest Neighbour):**				
1) K-nearest neighbours can be applied to both classification and regression problems.
2) The model seems to well fit data, but the model decay might be inevitable because of insufficient and unbalanced training set
3) KNNImputer is always better than simply filling with mean, median or even dropping null values
Accuracy when **K=3;**
**Accuracy = 96.97%**




# Home Page
![Screenshot](ss/ss0.png)
### 
![Screenshot](ss/ss2.png)
# Prediction with model accuracy
![Screenshot](ss/ss1.png)

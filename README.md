# FinalWork_ML
This is out Machine Learning final project, the subject is : given a dataset of differents sports pictures, we want to classify them according to 7 categories :<br>
basball, basketball, boxing, football, formula1, swimming, tennis and then run som Machine Learning algorithms on them.<br>
In this work, we respond to these questions :
* Are there groups that are more similar to each other ?
* Which sports are easy or difficult to distinguish between ?
* Is there any confusion between the sports photos ?
  
## Database
Our Dataset is from:
https://www.kaggle.com/datasets/ponrajsubramaniian/sportclassificationdataset
and we decided to modify it to have now a set of 3059 sports images, divided into 7 folders:
baseball, basketball, boxing, football, formula1, swimming and tennis.
The dataset is located on google drive as a zip file: 
https://drive.google.com/file/d/1dmX5laQwy4JYHSPHO2H7MX6JYzKRH7iO/view?usp=sharing
The number of baseball, basketball, boxing, football, formula1, swimming and tennis images is for 
each category 437 images.

## How to classify them ?
### Linear SVM
This model operates on the principle of dividing vectors using the greatest possible margin. It facilitates the division of data in multiple dimensions, enabling it to process images consisting of thousands of pixels.
### Clustering
It's a technique employed for clustering objects that resemble each other according to their features or qualities. This approach can be applied to classify and compress images. It involves organizing alike images by their visual qualities like color, texture, and form, as well as consolidating similar pixels to be represented by a singular value.
### Adaboost
Operates by amalgamating several "weak" classifiers to form a single "strong" classifier. Every weak classifier undergoes training on a data subset, with the algorithm increasing the weights of incorrectly classified data points. Subsequently, the next weaker classifier receives training on the revised data set, where the weights are adjusted to indicate the complexity of classifying each data point.
### K-Nearest-Neighbors
It determines the category of new data points by identifying the predominant class among its K closest neighbors within the feature space.
### Logistic Regression
Logistic regression is a supervised classification algorithm that models the probability an observation 
belongs to a specific category using a logistic function. Our implementation employs logistic 
regression to classify observations into multiple categories, optimizing hyperparameters through 
random search and evaluating performance using metrics like accuracy and the F1 score on a test 
set.


# Sklearn-Traintest

import sklearn
from sklearn import datasets

# load iris dataset
iris = datasets.load_iris()

# separate attributes and labels on dataset slices
x=iris.data
y=iris.target

from sklearn.model_selection import train_test_split
 
# dividing the dataset into training and testing
x_train, x_test, y_train, y_test = train_test_split(x, y, test_size=0.2, random_state=1)

# calculate the length or amount of data in each split directory
print(len(x))
print(len(x_train))
print(len(x_test))
print(len(y_train))
print(len(y_test))

# output
150
120
30
120
30

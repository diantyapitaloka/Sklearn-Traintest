# Sklearn-Traintest

- import sklearn
- from sklearn import datasets

# Load Iris Dataset
iris = datasets.load_iris()

# Separate Attributes and Labels on Dataset Slices
- x=iris.data
- y=iris.target

- from sklearn.model_selection import train_test_split
 
# Dividing the Dataset into Training and Testing
- x_train,
- x_test,
- y_train,
- y_test = train_test_split(x, y, test_size=0.2, random_state=1)

# Calculate The Length or Amount of Data in Each Split Directory
- print(len(x))
- print(len(x_train))
- print(len(x_test))
- print(len(y_train))
- print(len(y_test))

# Output
- 150
- 120
- 30
- 120
- 30

![image](https://github.com/diantyapitaloka/Sklearn-Traintest/assets/147487436/61ab5605-73b7-44fb-8d02-f58e6d0a0e7e)


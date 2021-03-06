# MNIST-Training(ANN vs CNN)
The major difference between a traditional Artificial Neural Network (ANN) and CNN is that only the last layer of a CNN is fully connected whereas in ANN, each neuron is connected to every other neurons.
CNN tends to be a more powerful and accurate way of solving classification problems. ANN is still dominant for problems where datasets are limited, and image inputs are not necessary.
## ANN vs CNN
![image](https://user-images.githubusercontent.com/90707178/161096903-cfb97b2c-4f9a-4355-82b8-e983e454e898.png)
![image](https://user-images.githubusercontent.com/90707178/161097216-b12a7aca-9dbe-49f7-a61b-ca9313f16f1a.png)




## MNIST Dataset
![image](https://user-images.githubusercontent.com/90707178/161095038-3d76f574-c21a-4b5c-881c-858870508c0f.png)


This repository is of CNN training of MNIST dataset Model.
First step is to visualize dataset given. Download the dataset in the csv format from the link: https://www.kaggle.com/datasets/oddrationale/mnist-in-csv?select=mnist_train.csv
This dataset contains two csv files, one is training dataset and another is test dataset.
After downloading the dataset, go through the dataset to get an idea that what is given in it. You can see in MNIST data visualization.ipynb 
After that try to make an ANN model and tune some parameters to get the different results to understand better.
Here ANN model gives about 98.5% of accuracy.
Now train the dataset with the CNN model(refer MNIST CNN.ipynb) and tune the parameters to get different results as done above.
Here CNN model gives about 99.26% of accuracy.
Now extract some data from the test.csv file and test the accuracy of the CNN model.

Image Reference:https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.tensorflow.org%2Fdatasets%2Fcatalog%2Fmnist&psig=AOvVaw2UGOJ0Pf3ieztsO9xkWhfK&ust=1648827639200000&source=images&cd=vfe&ved=0CAgQjRxqFwoTCNjwhJnY8PYCFQAAAAAdAAAAABAD


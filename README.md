## MNIST-digit-classification

#### Description :

In this project, I have created a simple deep learning model from scratch (on top of CNN) that is capable of identifying the digit present in an image.

#### Data :
Used the Keras - MNIST dataset. Each image size is 28 X 28. There are 70,000 datapoints in the dataset. 

#### Some sample images from the dataset :
![Sample Images](https://github.com/bhavani0387/MNIST-digit-classification/blob/main/Images.PNG?raw=true)

#### Methodology :
- Import required files
- Load the data from keras module
- Split the data into train and test
- Check the shapes of the tensors loaded
- Convert the target variables into One hot encoding  (ex :[2] - [0, 0, 0, 0, 0, 0, 0, 1, 0, 0]) since it was a classification task.
- Define the model
- Compile the model with a loss and optimizer
- Train the model.

#### Conclusion :
Got 98.96 training and 98.74 validation accuracy.

# dog-breed-classification

This project aims to classify dog pictures according to their breed. The database of images is retrieved from the [Stanford dogs dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/)  

## Description

The file P6_01_notebook.py makes some analysis on the database, creates a main Images folder of the 20 most present breeds. It also simplify folder names for targets and then creates a train and a test folder.   

We use two approaches : The first creating CNNs from scratch, the second using pre-trained neural networks : VGG16 and Resnet50.  

We then create a prediction function "P6_02_prediction_breed_function.py" with the model "my_model.h5" created with Resnet50.

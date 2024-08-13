# Detection-of-Lung-Infection-using-CNN
Detection of Lung Infection using a Convolutional Neural Network CNN


DESCRIPTION
Artificial Intelligence has evolved a lot and is currently able to solve problems that are very complex and require human specialization. One such area is healthcare.
 
A lot of research happens every day to use deep learning for the betterment of humanity, and one such is healthcare.
 
Objective:   
To build a model using a convolutional neural network that can classify lung infection in a person using medical imagery
 
Dataset Description:
The dataset contains three different classes, including healthy, type 1 disease, and type 2 disease.
 
•	Train folder: This folder has images for training the model, which is divided into subfolders having the same name as the class. 
•	Test folder: This folder has images for testing the model, which is divided into subfolders having the same name as the class.
 
Following operations should be performed using Keras or PyTorch or Torch vision-   
1.	Import the necessary libraries
2.	Plot the sample images for all the classes 
3.	Plot the distribution of images across the classes
4.	Build a data augmentation for train data to create new data with translation, rescale and flip, and rotation transformations. Rescale the image at 48x48
5.	Build a data augmentation for test data to create new data and rescale the image at 48x48
6.	Read images directly from the train folder and test folder using the appropriate function

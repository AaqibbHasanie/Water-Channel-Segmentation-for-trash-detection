This notebook is divided into 2 parts. 

**Part A**:

This part serves as a skelton coe to visualize the performance of any trained model for water channel segmentation on any dataset.

In order to execute part A, users just need water channels images and pre-trained weigts in the form of xyz.h5 file. Users can also obtain pre-trained model weights from internet and utilize them for this part.

**Part B**:

This part actually builds a compact neural network model for water channel segmentation to measure water contamination due to trash. In part B, I train the compact neural network on a dataset containing 5000 images of water channels and their segmented images. With only 75,459 trainable parameters, i was able to gain an IoU score of 0.76, Dice Coefficient of 0.82 and a validation accuracy of 0.82.

**Note**:
The dataset has not been shared due to licencing issues. Users are free to use any other dataset of their choice. Similarly, for the model.h5 file, users are welcome to use any file from internet.

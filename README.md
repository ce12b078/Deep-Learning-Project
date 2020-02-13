# Deep-Learning-Project
**Hand written digit classifier using Convolutional Neural Network**

**We will use following three codes:**
**1_CNN_tuning_hyperparameters:** In the first code, we will start with a CNN with randomly selected hyper parameters. Thereafter we will tune these hyper parameters in three steps.

We will start with a CNN, having 4 CNN maps, each followed by BatchNormalization. We also used 2 MaxPool2D layers & 2 Dropout layers. Then we used 3 layers of dense network.
We will then tune the hyper parameters in following three steps:
1.	Tuning the activation function.
2.	Tuning no. of CNN maps, no. of filters in each CNN map, kernel size & no. of nodes in dense layers.
3.	Tuning batch size, epochs & dropout percentage.

**2_BatchNormalisation_and_EarlyStopping:** In this code, we will see the impact of batch normalisation and early stopping callback on CNN. Without batch normalisation, training time is much higher. Early stopping helps in preventing overfitting.
**3_Image_Augmentation_and_final_model:** In this code, we will use ImageDataGenerator to generate new images from train data images (using image augmentation technique). This technique helps in increasing the training data, which will help in building more accurate models.	

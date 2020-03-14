# Image-Classification-using-Keras

# 1. INTRODUCTION
The aim of this excercise is to do build a classifier and test it on a collection of images for a new task using Keras. Simple to deep convolutional neural networks will be employed to classify images directly into 5 classes of food dataset.

# 1.1 OVERVIEW
In order to classify several food dishes into its respective categories, following strategy is being used:

Step 1: Build a simple baseline model and train the food dataset on the model. Analyse its accuracy and loss using graphs.

Step 2: Build a bit more deeper model from scratch and train the food dataset on the model. Analyse its accuracy and loss using graphs. The aim is to check if there is a change in training accuracy after adding convolutional and maxpooling layers to the model.

Step 3: Preprocess the data by augmenting it in several ways. The aim is to analyse the effect of data augmentation on the accuracy of the same complex model. Also add drop out layers to reduce overfitting. Again, analyse the accuracy and loss calculated while trying to classify the data using graphs and confusion matrix.

Step 4: Tune Hyper parameters in the previous model from step 3.

Step 5: Fine tune a pre-trained model, VGG16 and pass the same pre processed dataset. The objective is to solve a new problem using transfer Learning. Transfer learning is the reuse of a pre-trained model, in this case VGG16. It is currently very popular in the field of Deep Learning because it enables you to train Deep Neural Networks with comparatively little data.[1] It is expected that the accuracy will increase and the loss will decrease as the model is already trained. Next step is to analyse the pre_trained model through visualizations.

[1] https://towardsdatascience.com/transfer-learning-946518f95666

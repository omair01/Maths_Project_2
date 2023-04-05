# Maths_Project_2
CNN &amp; Vit
Our project is based on image classification of cats and dogs using CNN and ViT (Visual transformers)
The dataset is taken from kaggle and it contains test and training sets and here is the link to it: https://www.kaggle.com/competitions/dogs-vs-cats/data


For preprocessing we used data generators, we have a CNN architecture consists of several convolutional layers followed by a flattening layer and a few fully connected layers
Model is trained using the adam optimizer  sparse categorical crossentropy loss function
Hyperparameter tuning is also done for better accuracy


Next we used ViT for better accuracy
As we all know transformer-based model is more effective at capturing long-range dependencies in the images so resulting model should have higher accuracy than the previous model

Vit model's training loss is decreasing over time, which is a good sign. Validation accuracy seems to have plateaued and even decreased towards the end of training, which may indicate that the model is overfitting to the training data and not generalizing well to new data.

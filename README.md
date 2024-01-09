# DogsCatsRecognition

The project performs a classification system that identifies whether a dog or a cat is in an image. 
A dataset containing 25.000 images of dogs and cats (12.500 with dogs and 12.500 with cats) were used. These images contain different breeds from each animal and are diversified in terms of several factors such as brightness and background. 

Data processing, testing and model training:

To work more easily with the images in the database, they were processed so that they are the same size and format.
To train the corresponding model, CNN (Convolutional Neural Network) was used. This way we learn the characteristics of the images that can be used to differentiate images of dogs from those of cats.
The already trained model is evaluated on a separate dataset to test how accurately dogs and cats are identified. The purpose of the evaluation is to check how well identification is done on models not seen before.
Once the model is trained and performs well with the tested dataset, it is used to identify new images of dogs and cats. The new images will be inserted into the trained model and will use the model output to make a prediction. 

Outcomes:

As you can see on the chart below we have around 78 for 10 iterations. ('x' axis represents iterations and 'y' axis accuracy).
The highest accuracy is observed at 8 iterations, where the loss is minimal.
In 'Loss Graph' we see it gradually decreasing.
Maximum accuracy is somewhere at 79.5 (val_loss: 0.4432 - val_accuracy: 0.7950) for 10 iterations.

![image](https://github.com/tania3145/DogsCatsRecognition/assets/93408254/357f5417-59f5-49b8-a945-b89b4fbf40a4)
![image](https://github.com/tania3145/DogsCatsRecognition/assets/93408254/0890603d-ec5c-48d0-b3ad-a92064e321c0)

Used:

Colab - IDE online;
Python - as a programming language;
TensorFlow - as a library for model training;
Kaggle - for retrieving the data set with images

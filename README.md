# DSND-dog-breed-classifier

The purpose of this project is to use a convolutional neural network (CNN) to predict dog breeds.  The pipeline is the evaluation of an image as a dog or a human, then a prediction of which dog breed the dog is, or which dog breed the human most resembles.  If the image is detected as neither a dog nor a human, the classifier will not run.

Files included:

## Dog app:
dog-app.ipynb is the python 3 file that can be run to classify dog images

## Images: 
The images folder has the test images for this project.

## Models:
The saved_models folder contains the models saved during this project

## Pre-computer bottleneck features for InceptionV3
https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogInceptionV3Data.npz

In summary, the performance of the pre-trained model I built far exceeded the hand made CNN model. The accuracy of the InceptionV3 model (pre-trained on ImageNet) reached 80% while my CNN was about 4%.  This improved performance can be attributed to the vast dataset on which the pre-trained model was built.  In particular, the pre-trained model was also exposed to many dog images, making it particularly ready to classify dog breeds.

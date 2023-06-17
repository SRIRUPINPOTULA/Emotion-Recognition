# Emotion-Recognition
Emotion Recognition using Convolutional Neural Networks
Dataset: https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset
The above dataset is choosen which consists of around 28821 images with 7 classes for training and for validation there are 7066 with 7 classes. 
The emotions that are considered are Angry, Disgust, Fear, Happy, Neutral, Sad and Surprise.
The image size is (48,48,3) which is a thing to address.
Since, the image size is minimal using the image datagenerator tried to zoomin the picture so, that the training can be done in a better way.
Reached a accuracy of 85% for 26 epochs.

Transfer Learning Approach:
For the use of model training, I have used InceptionV3 with known weights where the final dense layers are added inorder to classify. 

# Emotion-Recognition
Emotion Recognition using Convolutional Neural Networks

Technology Used: Python, Tensorflow, OpenCV

This reposirtory consists of Custom_CNN, Inception - Transfer Learnig and OpenCV-Emotion Recognition.
Custom_CNN file consists of the Custom Neural Network that was trained and the model.json and model_weights.h5 are gathered for best accuracy given epoch. These weights have been read and the new emotion model was generated to detect human face emotion using OpenCV. Haar Cascade is used which goes hand-in-hand with Neural Networks and also, Haar Cascade is used for face detection. THe same dataset was trained on Inception V3 which is a fine-tuned model the weights are gathered which resulted to have an accuracy of 79.30%.

Dataset Details: https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset

About the dataset: The above dataset is choosen which consists of around 28821 images with 7 classes for training and for validation there are 7066 with 7 classes.  The emotions that are considered are Angry, Disgust, Fear, Happy, Neutral, Sad and Surprise. The image size is (48,48,3) which is a thing to address.

